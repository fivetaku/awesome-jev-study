# jev.nvim

[한국어](../../ko/projects/266-jev-nvim.md) · [English](../../en/projects/266-jev-nvim.md)

- 목록: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L266) `README.md:266` @ `22570dcd` (CC0). fivetaku/awesome-jev 포크는 이 커밋으로 클론했다.
- 절: 검색·데이터
- 주소: https://github.com/valentynkit/jev.nvim
- 조회: 2026-09-22
- 깊이: 목록 문장과 대상 앞부분. 소스 추적이 아니다. 런타임 테스트가 아니다.

## 목록이 말하는 일

> - [jev.nvim](https://github.com/valentynkit/jev.nvim) - Neovim plugin that splits the current buffer into functions with Treesitter, asks Jev a plain-language question against each one, and lists the answers in the quickfix window ranked by probability.

Neovim 플러그인. Treesitter로 현재 버퍼를 함수 단위로 나누고, 함수마다 평범한 말로 물은 뒤, 확률 순으로 quickfix에 답을 올린다.

## 확인한 것

- 실행으로 확인, GitHub API 2026-09-22: `valentynkit/jev.nvim`, 스타 5, SPDX MIT, push 2026-09-19, 아카이브 False, 언어 Lua.
- 목록의 CC0은 이 저장소 코드에 미치지 않는다. 라이선스는 MIT이다.
- API 설명 한 줄: Neovim: ask the buffer a question, get a quickfix list. Treesitter splits functions, Jev scores each one, probabilities land as virtual text

## Jev의 역할

Jev는 나머지 시스템이 이미 가져온 문단, 행, 쿼리 사이에서 점수를 매기거나 거르거나 고른다. 목록은 이렇게 적는다. Neovim 플러그인. Treesitter로 현재 버퍼를 함수 단위로 나누고, 함수마다 평범한 말로 물은 뒤, 확률 순으로 quickfix에 답을 올린다. 검색 자체는 데이터베이스, 색인, 크롤러의 일이다. 이 페이지는 그 파이프라인을 따라가지 않았다.

## 설정

설정으로 적는 것은 목록 문장과 2026-09-22에 읽은 앞부분뿐이다. 저장소 소스는 열지 않았다.

목록 문장과 읽은 앞부분에는 이 항목의 엔드포인트, 모델 id, 키 변수, 질문 스키마가 없다.

공식 호출의 모양은 이 프로젝트의 설정이 아니다. 목록 시작 예제(README.md:102-159)는 `POST https://api.typesafe.ai/v1/systemone`, 환경변수 `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, 한 `state`에 Choice·Noul·Score를 같이 넣는다. Vercel에서는 `experimental_evaluate`와 id `typesafe-ai/jev`. 그 예제는 실행하지 않았다.

## LLM으로 같은 일을 했다면

추론. LLM은 검색 결과를 요약하거나 다시 쓴다. 필요한 것이 순위나 유지/폐기뿐이면, 버리고 말 문장을 생성하느라 비용을 낸 것이다. 점수를 돌려주는 판정기는, 산문이 여전히 필요하면 그 산문을 나중 호출에 남긴다.

## 스크립트로 같은 일을 했다면

추론. 키워드 순위와 필터는 질의어가 문서에 있을 때 동작한다. 바꿔 쓴 문장은 놓친다. 일치가 정말로 어휘 수준이면 그게 맞는 도구다.

## 이 페이지가 하지 않은 것

저장소 소스, 테스트, 저자 숫자의 재측정, 제3자 README 전문 인용은 없다. 역할이 목록 문장 너머로 보이면 그건 앞부분에서 확인된 문장만이다. LLM 절과 스크립트 절은 추론이다.
