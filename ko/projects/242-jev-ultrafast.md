# Jev Ultrafast

[한국어](../../ko/projects/242-jev-ultrafast.md) · [English](../../en/projects/242-jev-ultrafast.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L242) `README.md:242` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: Browser and computer-use agents (브라우저·컴퓨터 조작)
- 주소: https://github.com/browser-use/jev-ultrafast
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [Jev Ultrafast](https://github.com/browser-use/jev-ultrafast) - Browser agent from [Browser Use](https://github.com/browser-use). Jev picks an operation and a DOM element in one request; a small LLM writes text only for `TYPE_TEXT`. Zürich → London on Google Flights in ~7 s. Library, local inspector, and measurements included.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `browser-use/jev-ultrafast`, 스타 17568, SPDX MIT, push 2026-09-18, 아카이브 False, 언어 Python.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 MIT이다.
- API 설명 한 줄: Fastest and cheapest web agent
- 스타가 세 갈래다. 목록 칸은 ~2.9k (README.md:194). madewithjev 페이지 제목은 2026-09-22에 17.3k라고 했다. 같은 날 GitHub API는 browser-use/jev-ultrafast에 17568을 돌려줬다. 페이지는 수치를 API에서 읽으며 매일 움직인다고 했다. 어느 것도 목록의 ~2.9k를 다시 잰 값은 아니다.

## Jev의 역할

목록이 맞다면 Jev의 자리는 브라우저나 컴퓨터 조작 루프 안의 결정이다. 목록은 이렇게 적는다. Browser agent from [Browser Use](https://github.com/browser-use). Jev picks an operation and a DOM element in one request; a small LLM writes text only for `TYPE_TEXT`. Zürich → London on Google Flights in ~7 s. Library, local inspector, and measurements included. 페이지를 읽고 클릭을 실행하는 일은 일반 코드다. 이 페이지는 그 루프를 따라가지 않았고, 이 프로젝트가 픽셀을 본다고 말하지 않는다. 텍스트 상태이지 프레임이 아니라고 적은 것은 Doom 소개뿐이며, 그 문장을 다른 에이전트에 옮기지 않는다.

## 세팅

세팅으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 세팅이 아니다. 목록 퀵스타트(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 state에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM은 다음 행동을 문장으로 쓰고, 프로그램이 그 문장을 파싱한다. 런치 글의 벤더 보고 종단 범위는 Jev 70–500ms, 프론티어 3–329초다. 이 프로젝트의 측정이 아니다. 페이지를 기다리게 두는 루프에서는 그 차이가 설계를 가른다. 출력 토큰은 LLM 청구서에 남는다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 셀렉터와 고정된 클릭 순서다. DOM이 그대로면 더 싸고 결정적이다. 마크업이 바뀌면, 비슷한 컨트롤 중 어느 것이 이 작업의 것인지 판단하지 못한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
