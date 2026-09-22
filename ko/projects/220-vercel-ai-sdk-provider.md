# Vercel AI SDK provider

[한국어](../../ko/projects/220-vercel-ai-sdk-provider.md) · [English](../../en/projects/220-vercel-ai-sdk-provider.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L220) `README.md:220` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: SDK와 클라이언트
- 주소: https://ai-sdk.dev/providers/ai-sdk-providers/typesafe-ai
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [Vercel AI SDK provider](https://ai-sdk.dev/providers/ai-sdk-providers/typesafe-ai) - `@ai-sdk/typesafe-ai` with `experimental_evaluate`; use `typeSafeAi.evaluationModel('jev-latest')` or the Gateway id `typesafe-ai/jev`.

`@ai-sdk/typesafe-ai`와 `experimental_evaluate`. `typeSafeAi.evaluationModel('jev-latest')` 또는 Gateway id `typesafe-ai/jev`.

## 확인한 것

- 이 행에서 목록 문장 밖에 확인된 사실은 없다.

## Jev의 역할

이 저장소는 모델이 아니라 클라이언트다. Jev는 원격 System One 엔드포인트에 있다. 패키지는 그 호출을 한 언어로 적게 해 준다. 목록 문장: `@ai-sdk/typesafe-ai`와 `experimental_evaluate`. `typeSafeAi.evaluationModel('jev-latest')` 또는 Gateway id `typesafe-ai/jev`.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장이 이름까지 적는다: `@ai-sdk/typesafe-ai`, `typeSafeAi.evaluationModel('jev-latest')`, `typesafe-ai/jev`. 그것은 목록의 문장이지, 소스를 따라가 확인한 설정 파일이 아니다.

목록은 커뮤니티 클라이언트가 TypeSafe와 무관하다고 적는다 (README.md:213).

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 언어 바인딩은 부차적이다. LLM 경로는 system_one 자리를 채팅 완성으로 바꾸고 문장 파서를 더한다. 출력 토큰과, 문장이 선택지 밖으로 나갈 가능성을 안는다. 공식 시작 예제 모양은 목록 README.md:102-159에 있다. 이 페이지는 그것을 다시 실행하지 않았다.

## 스크립트로 같은 일을 했다면

추론. 결정을 규칙으로 적을 수 있으면 이 클라이언트도 Jev도 필요 없다. SDK가 설 자리는, 질문이 의미 판단이고 답이 코드가 적어 둔 선택지 안에 있어야 할 때다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
