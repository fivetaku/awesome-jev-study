# Recruiting

[한국어](../../ko/projects/389-recruiting.md) · [English](../../en/projects/389-recruiting.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L389) `README.md:389` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: Use cases by industry (산업별 유스케이스)
- 주소: https://docs.typesafe.ai/concepts/use-case-map
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> | Recruiting | Evaluate job-related evidence, match candidates to roles, route applications, escalate uncertain cases. |

## 확인한 것

- 이 행에서 목록 문장 밖에 확인된 사실은 없다.

## Jev의 역할

이 행은 저장소가 아니라 결정의 모양이다. 목록은 이렇게 적는다. Evaluate job-related evidence, match candidates to roles, route applications, escalate uncertain cases. 라벨 뒤의 분기는 코드가 가지도록 적혀 있다. 여기 프로젝트를 따라가진 않았고, 받아 온 use-case map 앞부분이 이 문장 전체와 같은지는 확인하지 않았다.

## 세팅

세팅으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

문서 행이다. 세팅은 목록이 적은 질문의 모양이다. 샘플은 실행하지 않았다.

공식 호출의 모양은 이 프로젝트의 세팅이 아니다. 목록 퀵스타트(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 state에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 같은 일을 LLM으로 하면 건마다 문단이 나온다. 돌릴 수는 있다. 코퍼스 전체에 싸게 돌리기는 어렵고, 문단에 임계값을 걸려면 파서가 또 필요하다. 목록의 요지는 반대 분할이다. 의미 질문은 모델, 임계값과 부수 효과는 코드.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 이미 구조화된 필드에 대해서만 이 일을 구현한다. 자유 문장의 의도, 긴급, 불만은 키워드 규칙이 떨어뜨리는 부분이다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
