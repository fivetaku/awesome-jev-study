# jev-t-rex-runner

[한국어](../../ko/projects/334-jev-t-rex-runner.md) · [English](../../en/projects/334-jev-t-rex-runner.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L334) `README.md:334` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 데모·게임
- 주소: https://github.com/joshlarsen/jev-t-rex-runner
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [jev-t-rex-runner](https://github.com/joshlarsen/jev-t-rex-runner) - The Chrome dinosaur game, played by Jev.

Chrome 공룡 게임을 Jev가 한다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `joshlarsen/jev-t-rex-runner`, 스타 0, SPDX BSD-3-Clause, push 2026-09-17, 아카이브 False, 언어 JavaScript.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 BSD-3-Clause이다.
- API 설명 한 줄: Chrome dino game played by Typesafe AI Jev model

## Jev의 역할

Jev의 자리는 다음 합법 수다. 게임 코드가 상태나 선택지로 만들어 넘긴 것 중에서 고른다. 목록은 이렇게 적는다. Chrome 공룡 게임을 Jev가 한다. 게임, 합법 수 생성, 입력 주입은 모델 밖에 있다. 이 페이지는 그것들을 따라가지 않았고, 저자가 보고한 속도·비용을 재측정하지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM은 수를 산문으로 말할 수 있다. 턴제이고 수를 파싱할 수 있으면 기다릴 수 있다. 실시간 루프는, 벤더가 보고한 앞선 모델의 응답 시간 3–329초가 자릿수라도 맞다면 기다릴 수 없다. 그 범위는 이 게임에서 재지 않았다. 반칙 수는 LLM에게는 파싱 문제이고 Choice에게는 구성 문제다. 목록의 체스 행은 선택지가 합법 수이므로 반칙이 불가능하다고 적는다.

## 스크립트로 같은 일을 했다면

추론. 시뮬레이터가 있으면 미니맥스나 휴리스틱이 모델 없이 전술을 둔다. 코드로 점수를 매길 수 없는 게임에서는 쓸모가 없고, 평가가 정확한 게임에서는 대개 텍스트 판정보다 세다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
