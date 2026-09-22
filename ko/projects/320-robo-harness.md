# robo-harness

[한국어](../../ko/projects/320-robo-harness.md) · [English](../../en/projects/320-robo-harness.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L320) `README.md:320` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 로봇·하드웨어
- 주소: https://github.com/grmkris/robo-harness
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [robo-harness](https://github.com/grmkris/robo-harness) - SO-101 arm workbench: a Jev decision runner picks bounded joint steps from typed candidate actions under a spend budget.

SO-101 팔 작업대. Jev 결정 실행기가 지출 한도 안에서, 타입이 있는 후보 동작 중 관절 이동을 고른다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `grmkris/robo-harness`, 스타 2, SPDX none, push 2026-09-21, 아카이브 False, 언어 TypeScript.
- API 설명 한 줄: SO-101 robot-arm agent workbench: Bun/Effect coordinator, React workbench, Python LeRobot motor owner

## Jev의 역할

Jev의 자리는 제어 루프 안의 이산적인 다음 행동이다. 모터, 설정값, 안전 인터록은 모델이 아니다. 목록은 이렇게 적는다. SO-101 팔 작업대. Jev 결정 실행기가 지출 한도 안에서, 타입이 있는 후보 동작 중 관절 이동을 고른다. 이 페이지는 루프를 따라가지 않았고 주기를 재측정하지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 공개 글이 벤더 보고로 적은, 앞선 모델이 응답하기까지 3–329초는, 수 헤르츠로 돌아야 하는 루프에 들어가지 않는다. 그 범위는 이 하드웨어에서 재지 않았다. LLM은 여전히 내부 루프 밖에서 느린 숙고형 행동을 고를 수 있다.

## 스크립트로 같은 일을 했다면

추론. 동역학을 알 때는 컨트롤러, 웨이포인트, PID가 맞는 도구다. 선택이 의미 판단일 때, 예를 들어 장애물이 양보해야 하는 대상인지는 틀린 도구다. 목록은 이 프로젝트가 어느 쪽인지 보여 주지 않는다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
