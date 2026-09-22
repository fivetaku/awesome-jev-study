# FAQ: What are Jev's limits?

[한국어](../../ko/projects/539-faq-what-are-jev-s-limits.md) · [English](../../en/projects/539-faq-what-are-jev-s-limits.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L539) `README.md:539` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 자주 묻는 질문
- 주소: 이 행에는 URL이 없다
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> Choice questions cap at 255 options. Text only — no images, audio, or video. Listed rate limits are 250,000 tokens/second and 1,200 requests/minute, and TypeSafe says they can change dynamically. Known failure modes of the current model are documented in [Jev 1.13 jaggedness](https://docs.typesafe.ai/model-jaggedness/jev-1.13).

Choice는 선택지 255개까지. 텍스트만이고 이미지, 오디오, 비디오는 없다. 적은 속도 제한은 초당 250,000토큰, 분당 1,200요청이며 TypeSafe는 동적으로 바뀔 수 있다고 한다. 현재 모델의 알려진 실패는 [Jev 1.13 들쭉날쭉](https://docs.typesafe.ai/model-jaggedness/jev-1.13)에 있다.

## 확인한 것

- 이 행에서 목록 문장 밖에 확인된 사실은 없다.

## Jev의 역할

이 행은 Jev 통합이 아니다. Jev에 대한 페이지, 글, 목록, FAQ 답이다. 목록은 이렇게 적는다. Choice는 선택지 255개까지. 텍스트만이고 이미지, 오디오, 비디오는 없다. 적은 속도 제한은 초당 250,000토큰, 분당 1,200요청이며 TypeSafe는 동적으로 바뀔 수 있다고 한다. 현재 모델의 알려진 실패는 [Jev 1.13 들쭉날쭉](https://docs.typesafe.ai/model-jaggedness/jev-1.13)에 있다. 프로젝트가 아닌 앞부분에서 복구할 호출 설정은 없다. 소셜 글의 문장은 확인된 사실로 취급하지 않는다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

이 행은 통합이 아니라서 호출 설정이 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 코드가 아니라 주장에 대한 것이다. 주장이 '채팅 모델이 늘어놓을 일을 Jev가 판단한다'이면, LLM이 그 일을 하면 늘어놓는 문장을 쓰고 사람이 파싱한다. 행이 포인터뿐이면 갈아 끼울 시스템이 없다.

## 스크립트로 같은 일을 했다면

추론. 경계는 같다. 스크립트는 기사나 소셜 글을 대체하지 않는다. 밑의 과제가 닫힌 결정이면, 스크립트는 규칙을 미리 적을 수 있는 경우에만 Jev를 대신한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
