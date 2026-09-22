# jev-codex-router

[한국어](../../ko/projects/294-jev-codex-router.md) · [English](../../en/projects/294-jev-codex-router.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L294) `README.md:294` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 모델 라우팅
- 주소: https://github.com/0xNatoshi/jev-codex-router
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [jev-codex-router](https://github.com/0xNatoshi/jev-codex-router) - Per-turn Codex routing: Jev picks model, thinking depth, and speed mode.

Codex 턴마다 경로를 나눈다. Jev가 모델, 생각의 깊이, 속도 모드를 고른다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `0xNatoshi/jev-codex-router`, 스타 209, SPDX MIT, push 2026-09-22, 아카이브 False, 언어 JavaScript.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 MIT이다.
- API 설명 한 줄: Per-turn model & reasoning routing for Codex, driven by Jev (TypeSafe System One): picks the model, thinking depth and speed mode for every turn.

## Jev의 역할

Jev의 Choice가 다음 모델, 스킬, 경로를 고른다. 생성이 있다면 그 선택 다음에 일어난다. 목록은 이렇게 적는다. Codex 턴마다 경로를 나눈다. Jev가 모델, 생각의 깊이, 속도 모드를 고른다. 이 페이지는 라우팅 규칙을 소스에서 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 채팅 모델에게 경로를 고르라고 시킬 수 있다. 결정 하나에 생성 한 번의 비용을 내고, 답은 경로 목록 밖으로 샐 수 있다. Choice는 넣어 주지 않은 경로의 이름을 짓지 못한다.

## 스크립트로 같은 일을 했다면

추론. 키워드, 길이, 파일 종류 규칙은 싸고 잘 부러진다. 경로가 정말로 그 신호를 따르면 충분하고, '어려움'이 문장의 속성이면 실패한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
