# Jev란

[한국어](../ko/what-is-jev.md) · [English](../en/what-is-jev.md)

이 페이지의 기준은 awesome-jev 목록 `22570dcd`와 2026-09-22에 받아 온 페이지다. 벤더가 적어 둔 숫자는 그대로 둔다. API를 호출해 재측정하지 않았다.

## 모델

Jev는 TypeSafe가 공개한 첫 System One 모델이다. 목록 배너는 생성된 문장 대신 Choice, Score, Noul이라는 타입이 있는 결정과 확률을 돌려준다고 적는다. 같은 날 받아 온 모델 페이지는 이것을 TypeSafe의 플래그십 모델이라 부르고 그 페이지의 모델은 모두 `POST /v1/systemone`으로 제공된다고 한다.

자연어를 읽는다. 목록 FAQ는 문장을 생성하지 않으므로, 넣어 준 선택지 밖의 값은 가능한 출력이 아니라고 한다 (README.md:521-523). 목록은 LLM의 대체가 아니라고도 한다. 자유 문장이 필요하면 Jev가 경로를 나누고 찾고 검증하고 막으며 LLM이 코드가 그은 경계 안에서 쓴다 (README.md:85).

## 질문 셋

목록(README.md:60-66)은 한 요청의 질문들이 같은 `state`에 대해 병렬로 돈다고 한다.

| 질문 | 결정 | 반환 |
|---|---|---|
| Choice | 넣어 준 목록에서 하나 | `choice`, `probabilities`, `confidence` |
| Score | 상태가 채점 기준의 어디쯤인지 | `score`, `probabilities`, `confidence` |
| Noul | 문장이 성립하는지 | `noul`, 0에서 1 |

Choice는 선택지를 255개까지 받는다. 그 문장은 Choice 문서와 목록 가격 표(README.md:97)에 있다. 모델 페이지의 문장은 아니다. 선택지를 더하면 토큰이 조금 든다는 말은 Choice 문서의 표현이다.

조합, 임계값, 그 다음 일은 코드가 가진다. 목록이 그대로 말한다 (README.md:68).

## 가격, 한도, 접근

목록의 표는 2026-09-18 스냅샷이라고 스스로 적는다 (README.md:89-100).

- 별칭 `jev-latest`, 목록이 적는 버전 `jev-1.13.0`
- `POST https://api.typesafe.ai/v1/systemone`
- 입력 100만 토큰당 $0.042, 출력 토큰 무료
- 초당 250,000토큰, 분당 1,200요청. 목록은 한도가 바뀔 수 있다고 한다
- Choice 선택지 255개
- 텍스트만. 이미지, 오디오, 비디오는 없다
- 직접 접근은 얼리 액세스 대기 명단
- 대기 명단 없이 가는 길, 목록의 문장대로: Vercel AI Gateway id `typesafe-ai/jev`, Cloudflare Workers AI id `typesafe/jev`

같은 주에 대조한 것:

- 모델 페이지, 문서. 가격 줄은 10억 토큰당 $42, 100만 토큰당 $0.042. 출력은 무료이고 입력으로 과금한다. 요청당 64k, `state`와 가장 긴 질문을 합쳐 32k. `jev-latest`와 `jev-preview`는 둘 다 `jev-1.13.0`. 지금 프리뷰 빌드는 없고 별칭은 움직일 수 있다. 목록의 표에는 64k와 32k가 없다.
- 공개 글, 문서, 저자 Diogo Almeida. LLM 입력은 $0.20에서 $10 / MTok. Jev는 $0.042 / MTok, 10억 토큰당 $42. 출력은 FREE. TypeSafe의 응답까지 70ms–500ms, 앞선 모델 3초에서 329초. RLCD는 Reinforcement Learning for Calibrated Decisions다. 목록은 RLHF가 사람이 선호하는 답을 최적화할 때 RLCD는 정직한 확률을 최적화한다고 적는다. 이 범위는 벤더의 비교다. `$40M`, `40 million`, `$40 `는 그 글에 없다. `40x`는 속도 배수다. FAQ의 "$40M을 모았다"(README.md:519)는 미확인이다.
- Vercel, 이번 조회, 실행. id `typesafe-ai/jev`는 있다. 화면 표시에는 32K와 Free가 있다. `0.042`와 `waitlist`는 없다. 목록의 가격과 "대기 명단 없음"을 이 페이지가 확인했다고 하지 않는다.
- Cloudflare, 문서. id `typesafe/jev`, 컨텍스트 32,000, `env.AI.run`. 가격 액수는 페이지에 없다. 예제 제목에 structured refund review, support department routing, account risk assessment가 있다.

목록은 얼리 액세스가 2026-09-15에 시작했다고 한다 (README.md:20). 그 날짜는 목록의 문장이다.

## 호출의 모양

목록 시작 예제(README.md:102-159)는 실행하지 않았다. 거기 적힌 것은 이렇다.

- TypeSafe 콘솔에서 키를 만든다. 클라이언트는 `TYPESAFE_API_KEY`를 읽는다.
- Python: `pip install typesafe-sdk`. 한 `state`에 `Choice`, `Noul`, `Score`를 넣어 `TypeSafeClient.system_one`.
- JavaScript: `npm install @typesafe-ai/sdk`. `choice`, `noul`, `score`로 `client.systemOne`.
- Vercel AI Gateway: `experimental_evaluate`와 모델 id `typesafe-ai/jev`.

받아 온 시작 예제 페이지는 같은 POST와 Bearer 인증을 보여 준다. 위의 Python 클래스 이름은 목록의 예제다.

에이전트 스킬 페이지는 목록의 설치 줄과 같다 (README.md:353). `claude plugin marketplace add typesafe-ai/skills`, 이어서 `claude plugin install typesafe@typesafe-ai`, 또는 `npx skills add typesafe-ai/skills --skill typesafe-ai`.

## 이 목록은 무엇인가

목록은 비공식이고 TypeSafe와 무관하다 (README.md:20, 꼬리 README.md:566). @kraayenjon이 madewithjev.com의 일부로 유지한다. CC0은 목록 문장에 미친다. 링크된 저장소에는 미치지 않는다. 그중 usenotra/notra는 AGPL-3.0이다. 이 스터디는 그 코드를 싣지 않는다.

대표 빌드의 비용과 지연은 저자 보고다. 목록이 그렇게 말한다 (README.md:209). 재측정하지 않았다.
