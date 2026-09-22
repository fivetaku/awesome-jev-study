# SkillRanker

[한국어](../../ko/projects/362-skillranker.md) · [English](../../en/projects/362-skillranker.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L362) `README.md:362` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 에이전트 도구·MCP
- 주소: https://github.com/Dicklesworthstone/skillranker
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [SkillRanker](https://github.com/Dicklesworthstone/skillranker) - Rust CLI: Jev ranks which agent skill fits the next step from live session context, with Claude Code hooks.

Rust CLI. 지금 세션 문맥으로 다음 단계에 맞는 에이전트 스킬 순위를 Jev가 매긴다. Claude Code 훅이 있다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `Dicklesworthstone/skillranker`, 스타 112, SPDX NOASSERTION, push 2026-09-22, 아카이브 False, 언어 Rust.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 NOASSERTION이다.
- API 설명 한 줄: Rust CLI powered by Jev from TypeSafe.ai that ranks agent skills for the next step using live session context. Includes Claude Code hooks, structured JSON, abstention, and local fe

## Jev의 역할

Jev는 에이전트가 부르는 도구로 열려 있거나, 이미 문장을 쓰는 에이전트 앞의 게이트다. 목록은 이렇게 적는다. Rust CLI. 지금 세션 문맥으로 다음 단계에 맞는 에이전트 스킬 순위를 Jev가 매긴다. Claude Code 훅이 있다. 에이전트 루프, 권한, 그 다음 일은 Jev가 아니다. 이 페이지는 그것들을 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 에이전트는 이미 LLM 경로다. Jev가 바꾸는 것은 즉흥이면 안 되는 순간뿐이다. 판정, 경로, 멈춤/진행. 그 순간을 같은 채팅 모델에 남기면 판정은 선택지 없는 산문이 된다.

## 스크립트로 같은 일을 했다면

추론. 스크립트로 짠 훅은 정규식이나 빠진 테스트에서 막을 수 있다. 코드로 적지 않은 자연어 완료 규칙은 적용하지 못한다. 목록의 스톱훅 행은 그 구분을 주장한다. 소스는 열지 않았다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
