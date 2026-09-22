# console cookbooks

[한국어](../../ko/projects/425-console-cookbooks.md) · [English](../../en/projects/425-console-cookbooks.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L425) `README.md:425` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 따라 하는 예제
- 주소: https://console.typesafe.ai/docs/cookbooks
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> Official, copy-pasteable workflows. Full index: [console cookbooks](https://console.typesafe.ai/docs/cookbooks) and the [docs index](https://docs.typesafe.ai/llms.txt).

공식이고, 붙여 넣어 쓰는 워크플로. 전체 색인: [콘솔 쿡북](https://console.typesafe.ai/docs/cookbooks)과 [문서 색인](https://docs.typesafe.ai/llms.txt).

## 확인한 것

- 이 행에서 목록 문장 밖에 확인된 사실은 없다.

## Jev의 역할

이 행은 레시피다. 목록은 이렇게 적는다. 공식이고, 붙여 넣어 쓰는 워크플로. 전체 색인: [콘솔 쿡북](https://console.typesafe.ai/docs/cookbooks)과 [문서 색인](https://docs.typesafe.ai/llms.txt). 목록이 보여주는 설정은 `state`와 Choice·Noul·Score 질문이고, 임계값은 코드에 남긴다. 레시피는 실행하지 않았다. 커뮤니티 쿡북 코드는 복사하지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

문서 행이다. 설정은 목록이 적은 질문의 모양이다. 샘플은 실행하지 않았다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 쿡북 단계를 LLM으로 하면 분류를 문장으로 생성하거나 사용자에게 직접 답한다. 닫힌 선택지를 잃고, 배치의 모든 행에서 출력 토큰을 낸다. 인용 확인처럼 다시 쓴 문단이 아니라 판단이 필요한 레시피는 거기서 맞지 않게 된다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 목록이 이미 코드에 맡긴 비의미 절반을 할 수 있다. 날짜를 해석하고, 범위를 검증하고, 임계값을 적용한다. 인용이 주장을 뒷받침하는지 같은 의미 절반은 정규식이 근사할 뿐이다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
