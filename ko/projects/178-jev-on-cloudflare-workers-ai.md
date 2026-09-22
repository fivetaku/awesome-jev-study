# Jev on Cloudflare Workers AI

[한국어](../../ko/projects/178-jev-on-cloudflare-workers-ai.md) · [English](../../en/projects/178-jev-on-cloudflare-workers-ai.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L178) `README.md:178` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 공식 자료
- 주소: https://developers.cloudflare.com/ai/models/typesafe/jev/
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [Jev on Cloudflare Workers AI](https://developers.cloudflare.com/ai/models/typesafe/jev/) - `typesafe/jev` via `env.AI.run`, with worked support-routing and risk-escalation examples.

`env.AI.run`으로 부르는 `typesafe/jev`. 지원 라우팅과 위험 상향의 예가 있다.

## 확인한 것

- Cloudflare 문서: 모델 id `typesafe/jev`, 컨텍스트 32,000, 호출은 `env.AI.run`. 가격 액수는 페이지에 없고 대시보드로 보낸다. 예제 제목에 structured refund review, support department routing, account risk assessment가 있다. 목록의 'support-routing and risk-escalation'과 겹치지만 같은 문장은 아니다.

## Jev의 역할

이 행은 커뮤니티 통합이 아니라 TypeSafe 페이지이거나 목록 자신의 표다. 다루는 것: `env.AI.run`으로 부르는 `typesafe/jev`. 지원 라우팅과 위험 상향의 예가 있다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장이 이름까지 적는다: `typesafe/jev`. 그것은 목록의 문장이지, 소스를 따라가 확인한 설정 파일이 아니다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 목록이 긋는 비교는 구조다. LLM은 문장을 쓰고 사람이 파싱한다. Jev는 정해 둔 공간 안의 값을 돌려준다. 모델만 바꾸면 결과의 타입이 유지되지 않는다. 공개 글의 지연·가격 범위는 벤더 보고이고 이 페이지의 재실행이 아니다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 결정 주위의 제어 흐름을 짤 수 있고, 규칙이 이미 코드일 때만 결정 자체를 대신한다. 모델을 설명하려고 있는 페이지를 스크립트가 대체하지는 못한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
