# PocketJev

[한국어](../../ko/projects/471-pocketjev.md) · [English](../../en/projects/471-pocketjev.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L471) `README.md:471` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 연구·오픈 모델
- 주소: https://github.com/NullPo-jp/PocketJev
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [PocketJev](https://github.com/NullPo-jp/PocketJev) - On-device iPhone visual decisions with MLX + Qwen3-VL option logits. Camera + 3-choice, no text generation, ~1 s, no photo saved.

아이폰에서 MLX와 Qwen3-VL 선택지 로짓으로 보는 결정. 카메라와 선택지 3개, 글 생성 없음, 약 1초, 사진은 저장하지 않는다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `NullPo-jp/PocketJev`, 스타 1, SPDX MIT, push 2026-09-17, 아카이브 False, 언어 Swift.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 MIT이다.
- API 설명 한 줄: On-device iPhone visual decision tool using MLX and Qwen3-VL direct option logits.

## Jev의 역할

이 행은 주장 옆에 놓인 논문, 로컬 모델, 오픈 산출물이다. 목록은 이렇게 적는다. 아이폰에서 MLX와 Qwen3-VL 선택지 로짓으로 보는 결정. 카메라와 선택지 3개, 글 생성 없음, 약 1초, 사진은 저장하지 않는다. Jev를 의존성으로 가정하지 않는다. 앞부분이 Jev의 이름을 말하는지까지 보았다. 소스는 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. 산출물 자체가 언어 모델이면 차이는 과제다. Jev는 답 문장을 생성하지 않는다. 로컬 LLM은 생성한다. 누군가 닫힌 결정을 흉내 내도록 학습시키지 않았다면. 목록의 한 행은 Qwen 위의 작은 MLP가 그렇게 한다고 주장한다. 그 주장은 여기서 시험하지 않았다.

## 스크립트로 같은 일을 했다면

추론. 스크립트는 평가의 채점 규칙을 재현할 수 있다. 학습된 결정은 재현하지 못한다. 연구 행을 가져다 쓸 라이브러리로 보는 것은 범주의 실수다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
