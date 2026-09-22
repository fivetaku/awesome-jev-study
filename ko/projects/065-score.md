# Score

[한국어](../../ko/projects/065-score.md) · [English](../../en/projects/065-score.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L65) `README.md:65` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: What is Jev? (Jev가 뭔가)
- 주소: https://docs.typesafe.ai/primitives/score
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> | [Score](https://docs.typesafe.ai/primitives/score) | Rate the state on a rubric | `score`, `probabilities`, `confidence` |

## 확인한 것

- 목록이 같이 적은 숫자: `score`, `probabilities`, `confidence`. 저자 보고이다 (README.md:209). 재측정하지 않았다.

## Jev의 역할

이 행은 제3자 앱이 아니라 질문 타입이다. Jev의 역할은 질문 그것이다. Rate the state on a rubric Choice는 적어 둔 선택지 중 하나를 고른다. Score는 상태를 루브릭 위에 놓는다. Noul은 문장이 성립하는지를 0에서 1로 답한다. 목록은 한 요청의 질문들이 같은 state에 대해 병렬로 돈다고 적는다 (README.md:60).

## 세팅

세팅으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

문서 행이다. 세팅은 목록이 적은 질문의 모양이다. 샘플은 실행하지 않았다.

공식 호출의 모양은 이 프로젝트의 세팅이 아니다. 목록 퀵스타트(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 state에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM은 산문으로 답한다. 그 문장에서 라벨을 파싱해야 하고, 라벨은 제시하지 않은 단어일 수 있다. 출력 토큰도 비용이다. Jev의 답은 질문에 들어 있는 값 하나와 확률이다. 런치 글의 벤더 보고는 Jev 종단 70–500ms, 프론티어 3–329초, LLM 입력 $0.20–$10 / MTok, Jev 입력 $0.042에 출력 무료다. 이 행을 재측정한 값은 아니다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 규칙이 이미 닫혀 있을 때만 라벨을 돌려준다. 키워드, 정규식, 필드 임계값. 같은 의도의 새 문장은 읽지 못한다. 규칙이 정말로 닫혀 있으면 스크립트가 더 맞는 도구이고 Jev는 필요 없다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
