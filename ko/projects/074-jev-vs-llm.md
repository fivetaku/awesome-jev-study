# Jev vs LLM 표

[한국어](../../ko/projects/074-jev-vs-llm.md) · [English](../../en/projects/074-jev-vs-llm.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L74) `README.md:74` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: Jev와 LLM
- 주소: https://typesafe.ai/blog/introducing-system-one-models-and-jev
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

이 행은 한 줄 불릿이 아니다. 아래 인용은 목록의 그 줄이고, 이어서 표나 블록을 한국어로 옮긴다.

> The list's table (README.md:74-85), which it attributes to the launch post. Existing LLMs versus System One + Jev: RLHF or RLVR versus RLCD, strings that need parsing versus typed values, token by token versus one parallel query, $0.20–$10 / MTok with output about five times more versus $0.042 / MTok with output free, vendor-reported 3–329 s versus 70–500 ms, overconfident if asked versus calibrated confidence, chat and open-ended work versus decisions inside software. The table does not claim an accuracy win. The following sentence says Jev is not an LLM replacement.

목록의 표(README.md:74-85). 목록은 이것을 공개 글에서 가져왔다고 한다. 기존 LLM과 System One + Jev를 나란히 놓는다. RLHF·RLVR 대 RLCD, 파싱이 필요한 문자열 대 타입이 있는 값, 토큰을 하나씩 대 한 번의 병렬 질문, 입력 $0.20–$10 / MTok에 출력이 약 다섯 배 대 입력 $0.042 / MTok에 출력 무료, 벤더가 보고한 3–329초 대 70–500ms, 물으면 과신 대 보정된 확신, 대화와 열린 작업 대 소프트웨어 안의 결정. 표는 정확도에서 이겼다고 하지 않는다. 다음 문장은 Jev가 LLM을 대체하지 않는다고 한다.

## 확인한 것

- 공개 글 이번 조회: 저자 Diogo Almeida. LLM 입력은 $0.20 to $10 / MTok. Jev 입력은 $0.042 / MTok, 출력 FREE. TypeSafe의 응답까지 70ms–500ms, 앞선 모델 3 to 329 seconds. RLCD는 Reinforcement Learning for Calibrated Decisions. `$40M`, `40 million`, `$40 `는 없다. `40x`는 속도 배수다.

## Jev의 역할

이 행은 커뮤니티 통합이 아니라 TypeSafe 페이지이거나 목록 자신의 표다. 다루는 것: 목록의 표(README.md:74-85). 목록은 이것을 공개 글에서 가져왔다고 한다. 기존 LLM과 System One + Jev를 나란히 놓는다. RLHF·RLVR 대 RLCD, 파싱이 필요한 문자열 대 타입이 있는 값, 토큰을 하나씩 대 한 번의 병렬 질문, 입력 $0.20–$10 / MTok에 출력이 약 다섯 배 대 입력 $0.042 / MTok에 출력 무료, 벤더가 보고한 3–329초 대 70–500ms, 물으면 과신 대 보정된 확신, 대화와 열린 작업 대 소프트웨어 안의 결정. 표는 정확도에서 이겼다고 하지 않는다. 다음 문장은 Jev가 LLM을 대체하지 않는다고 한다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

문서 행이다. 설정은 목록이 적은 질문의 모양이다. 샘플은 실행하지 않았다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 목록이 긋는 비교는 구조다. LLM은 문장을 쓰고 사람이 파싱한다. Jev는 정해 둔 공간 안의 값을 돌려준다. 모델만 바꾸면 결과의 타입이 유지되지 않는다. 공개 글의 지연·가격 범위는 벤더 보고이고 이 페이지의 재실행이 아니다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 결정 주위의 제어 흐름을 짤 수 있고, 규칙이 이미 코드일 때만 결정 자체를 대신한다. 모델을 설명하려고 있는 페이지를 스크립트가 대체하지는 못한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
