# citation-verifier

[한국어](../../ko/projects/310-citation-verifier.md) · [English](../../en/projects/310-citation-verifier.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L310) `README.md:310` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 업무용 앱
- 주소: https://github.com/MarissaFamularo/citation-verifier
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [citation-verifier](https://github.com/MarissaFamularo/citation-verifier) - Checks whether each cited paper actually supports the sentence citing it: Claude locates the quote, Jev scores the support, a human makes the final call.

인용한 논문이 그 문장을 받치는지 본다. Claude가 인용 위치를 찾고, Jev가 뒷받침 정도를 점수로 매기며, 마지막 판단은 사람이다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `MarissaFamularo/citation-verifier`, 스타 5, SPDX MIT, push 2026-09-17, 아카이브 False, 언어 JavaScript.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 MIT이다.
- API 설명 한 줄: Check whether each cited paper supports the sentence citing it. Claude proves the quote, TypeSafe's Jev scores it, a human decides.

## Jev의 역할

목록은 이렇게 적는다. 인용한 논문이 그 문장을 받치는지 본다. Claude가 인용 위치를 찾고, Jev가 뒷받침 정도를 점수로 매기며, 마지막 판단은 사람이다. 이 절의 행은 대개 닫힌 라벨이다. 채용 여부, 의도, 매수·매도, 허용·차단. 돈, 메시지, 기록은 일반 코드에 남는다. 그 예는 절의 예이고, 이 행이 그중 하나라는 확인은 아니다. 이 페이지는 그 다음 일을 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM은 이유를 산문으로 쓴다. 일괄로 돌리기도, 임계값을 걸기도 더 어렵다. 사람이 이유를 읽어야 하면 그게 맞고, 같은 판단 천 건이면 맞지 않는다.

## 스크립트로 같은 일을 했다면

추론. 구조화된 필드의 규칙은 신호가 이미 컬럼일 때 동작한다. 키워드를 반복하지 않는 자유 문장에서는 실패한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
