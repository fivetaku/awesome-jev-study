# commit-miner

[한국어](../../ko/projects/278-commit-miner.md) · [English](../../en/projects/278-commit-miner.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L278) `README.md:278` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 개발 도구·코드 리뷰
- 주소: https://github.com/devanshbatham/commit-miner
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [commit-miner](https://github.com/devanshbatham/commit-miner) - Rust CLI that classifies commit diffs: bug fixes, security/CWEs, and change types. HTML/CSV reports.

커밋 diff를 분류하는 Rust CLI. 버그 수정, 보안과 CWE, 변경 종류. HTML과 CSV 보고.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `devanshbatham/commit-miner`, 스타 35, SPDX none, push 2026-09-17, 아카이브 False, 언어 Rust.
- API 설명 한 줄: Classify Git commit diffs and messages with Jev. Bug fixes, security fixes/CWEs, and change types.

## Jev의 역할

목록은 이렇게 적는다. 커밋 diff를 분류하는 Rust CLI. 버그 수정, 보안과 CWE, 변경 종류. HTML과 CSV 보고. 이 절에 모인 행은 대개 diff, 로그, 커밋, 이미 뽑아 둔 문자열에 대한 판단이고, 파일시스템과 git 호출은 일반 코드가 가진다. 그것은 절의 모양이다. 이 행이 그렇게 생겼다는 확인은 아니다. 이 페이지는 그 코드를 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM 리뷰는 코멘트를 쓴다. 산문이 목표면 그게 더 나은 산출물이다. 임계값을 걸고 저장하고 실행끼리 비교할 라벨이 목표면 더 나쁜 산출물이다. 출력 토큰과 닫히지 않은 문장이 비용이다.

## 스크립트로 같은 일을 했다면

추론. 린트와 정규식은 받은 패턴에 정확하다. 알려진 형태의 비밀도 그렇다. 풀 리퀘스트가 주장한 일을 그 변경이 하는지는 판단하지 못한다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
