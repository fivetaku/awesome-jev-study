# 가격·한도 표

[한국어](../../ko/projects/091-item.md) · [English](../../en/projects/091-item.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L91) `README.md:91` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 가격·한도·접근
- 주소: https://docs.typesafe.ai/models
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

이 행은 한 줄 불릿이 아니다. 아래 인용은 목록의 그 줄이고, 이어서 표나 블록을 한국어로 옮긴다.

> The list's price table (README.md:91-100), a snapshot it dates September 18, 2026. `jev-latest` is `jev-1.13.0`. Endpoint `POST https://api.typesafe.ai/v1/systemone`. $0.042 / 1M input tokens, output free. 250,000 tokens/second and 1,200 requests/minute. Choice up to 255 options. Text only. Direct access is a waitlist. The list's no-waitlist path is Vercel (`typesafe-ai/jev`) and Cloudflare (`typesafe/jev`).

목록의 가격 표(README.md:91-100). 2026-09-18 스냅샷이라고 스스로 적는다. `jev-latest`는 `jev-1.13.0`이다. 엔드포인트는 `POST https://api.typesafe.ai/v1/systemone`. 입력 100만 토큰당 $0.042, 출력은 무료. 초당 250,000토큰, 분당 1,200요청. Choice 선택지는 255개. 텍스트만 받는다. 직접 접근은 대기 명단이다. 목록이 대기 명단 없이 간다고 적은 길은 Vercel(`typesafe-ai/jev`)과 Cloudflare(`typesafe/jev`)다.

## 확인한 것

- 모델 페이지 이번 조회: 요청당 64k, `state`와 가장 긴 질문을 합쳐 32k. `jev-latest`와 `jev-preview`는 둘 다 `jev-1.13.0`. 출력 토큰은 무료. 지금 프리뷰 빌드는 없다고 한다. 목록의 가격 표(README.md:91-100)에는 64k와 32k가 없다. Choice 상한 255는 모델 페이지 문장이 아니라 Choice 문서와 목록 README.md:97에 있다.

## Jev의 역할

이 행은 커뮤니티 통합이 아니라 TypeSafe 페이지이거나 목록 자신의 표다. 다루는 것: 목록의 가격 표(README.md:91-100). 2026-09-18 스냅샷이라고 스스로 적는다. `jev-latest`는 `jev-1.13.0`이다. 엔드포인트는 `POST https://api.typesafe.ai/v1/systemone`. 입력 100만 토큰당 $0.042, 출력은 무료. 초당 250,000토큰, 분당 1,200요청. Choice 선택지는 255개. 텍스트만 받는다. 직접 접근은 대기 명단이다. 목록이 대기 명단 없이 간다고 적은 길은 Vercel(`typesafe-ai/jev`)과 Cloudflare(`typesafe/jev`)다.

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
