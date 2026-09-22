# 1kpapers

[한국어](../../ko/projects/200-1kpapers.md) · [English](../../en/projects/200-1kpapers.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L200) `README.md:200` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: Featured builds with real numbers (숫자가 붙은 빌드)
- 주소: https://madewithjev.com/builds/1kpapers
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> | [1kpapers](https://madewithjev.com/builds/1kpapers) | A corpus classified by topic and published as a site | 1,018 papers | [Site](https://www.1kpapers.com/) |

## 확인한 것

- 목록이 같이 적은 숫자: 1,018 papers. 저자 보고이다 (README.md:209). 재측정하지 않았다.

## Jev의 역할

Jev는 저자가 이미 모아 둔 더미의 모든 항목에 같은 닫힌 질문을 한다. 목록은 이렇게 적는다. A corpus classified by topic and published as a site 그 문장 옆의 숫자는 저자 보고다. README.md:209는 목록이 재지 않았다고 적는다. 이 스터디도 재지 않았다.

## 세팅

세팅으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 세팅이 아니다. 목록 퀵스타트(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 state에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM도 같은 더미를 분류할 수 있고, 라벨보다 많은 문장을 쓴다. 비용과 시간은 출력 길이에 따라 커진다. 런치 글의 벤더 보고 가격은 LLM 입력 $0.20–$10 / MTok에 출력을 더하고, Jev는 $0.042 / MTok에 출력이 무료다. 그 단가를 이 저자의 토큰 수에 곱하는 것은 이 스터디가 하지 않는 새 계산이다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 적어 둔 규칙, 키워드 목록이나 정확한 필드로만 코퍼스를 분류한다. 이미 구조화된 컬럼에는 맞는 도구이고, 다음 표현으로 일반화하지는 못한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
