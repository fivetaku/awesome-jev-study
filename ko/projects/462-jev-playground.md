# Jev Playground

[한국어](../../ko/projects/462-jev-playground.md) · [English](../../en/projects/462-jev-playground.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L462) `README.md:462` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: Benchmarks and evaluations (벤치마크)
- 주소: https://github.com/hegargarcia/jev-playground
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [Jev Playground](https://github.com/hegargarcia/jev-playground) - Benchmarks Jev against Luna, Haiku, and Gemini at choosing validated legal moves in explicit-state games.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `hegargarcia/jev-playground`, 스타 0, SPDX none, push 2026-09-17, 아카이브 False, 언어 TypeScript.

## Jev의 역할

이 행은 제품 기능이 아니라 하네스이거나 공개 평가다. 목록은 이렇게 적는다. Benchmarks Jev against Luna, Haiku, and Gemini at choosing validated legal moves in explicit-state games. 목록의 공식 숫자는 벤더 보고다. 이 스터디는 하네스를 다시 돌리지 않았다. 2026-09-22의 evals.typesafe.ai 조회 본문에는, 더 긴 이전 추출이 인용하던 대표 백분율이 없었다. 그래서 그 백분율은 여기 다시 적지 않는다.

## 세팅

세팅으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 세팅이 아니다. 목록 퀵스타트(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 state에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 이 행들에서 LLM은 대개 비교 대상이지, 하네스를 갈아 끼우는 부품이 아니다. Jev를 LLM으로 바꾸면 비용의 단위가 입력 과금 결정에서 생성된 답으로 바뀌고, 지연은 벤더가 보고한 간격만큼 바뀐다. 그것만으로 벤치마크가 재현되지는 않는다.

## 스크립트로 같은 일을 했다면

추론. 정확 일치나 어휘 순위 같은 스크립트 기준선은 하네스가 그것을 포함할 때만 의미가 있다. 목록 문장이 그렇게 말하기 전에는 포함한다고 하지 않는다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
