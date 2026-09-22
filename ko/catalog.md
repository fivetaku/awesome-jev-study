# 항목

[한국어](../ko/catalog.md) · [English](../en/catalog.md)

각 페이지는 목록 문장, 확인된 사실, Jev의 역할, 설정, LLM이었다면, 스크립트였다면.

282개. 소스 추적은 없다.


## 앞부분

- [Submit yours →](projects/018-submit-yours.md) — README.md:18 — 제출 페이지는 링크 하나를 받는다. 페이지는 Jev가 그 링크를 읽고, 실을 만한지 판단하고, 분류한다고 한다. 등재는 무료이고, 돈을 내고 자리를 살 수 없다고 페이지가 말한다.
- [madewithjev.com](projects/018-madewithjev-com.md) — README.md:18 — madewithjev.com은 사람들이 Jev로 만든 것을 모아 둔 디렉터리다. 목록은 빌드마다 저자가 보고한 비용, 지연, 출처가 붙는다고 한다.

## Jev란

- [Choice](projects/064-choice.md) — README.md:64 — 적어 둔 선택지 가운데 하나를 고른다.
- [Score](projects/065-score.md) — README.md:65 — 상태를 채점 기준 위에 놓아 점수를 매긴다.
- [Noul](projects/066-noul.md) — README.md:66 — 이 문장이 맞는지 답한다.

## Jev와 LLM

- [Jev vs LLM 표](projects/074-jev-vs-llm.md) — README.md:74 — 목록의 표(README.md:74-85). 목록은 이것을 공개 글에서 가져왔다고 한다. 기존 LLM과 System One + Jev를 나란히 놓는다. RLHF·RLVR 대 RLCD, 파싱이 필요한 문자열 대 타입이 있는 값, 토큰을 하나씩 대 한 번의 병렬 질문, 입력 $0.20–...

## 가격·한도·접근

- [가격·한도 표](projects/091-item.md) — README.md:91 — 목록의 가격 표(README.md:91-100). 2026-09-18 스냅샷이라고 스스로 적는다. `jev-latest`는 `jev-1.13.0`이다. 엔드포인트는 `POST https://api.typesafe.ai/v1/systemone`. 입력 100만 토큰당 $0.042, ...
- [typesafe.ai](projects/099-typesafe-ai.md) — README.md:99 — 얼리 액세스는 [typesafe.ai](https://typesafe.ai)의 대기 명단으로 들어간다.
- [Vercel AI Gateway](projects/100-vercel-ai-gateway.md) — README.md:100 — [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev)의 `typesafe-ai/jev`와 [Cloudflare Workers AI](https://developers.cloudflare.com/ai/models/typesaf...

## 시작 예제

- [퀵스타트 예제](projects/102-item.md) — README.md:102 — 목록의 시작 예제(README.md:102-159). 여기서 실행하지 않았다. Python은 `pip install typesafe-sdk`, 클래스 `Choice`·`Noul`·`Score`, `TypeSafeClient.system_one`, 키는 `TYPESAFE_API_KE...

## 공식 자료

- [TypeSafe AI](projects/163-typesafe-ai.md) — README.md:163 — 회사 홈, 대기 명단, 제품 개요.
- [Introducing System One Models and Jev](projects/164-introducing-system-one-models-and-jev.md) — README.md:164 — 창업자 Diogo Almeida의 공개 글. 구조, RLCD, 가격, Doom과 Wikiracing 데모, 자주 묻는 질문이 들어 있다.
- [Documentation](projects/165-documentation.md) — README.md:165 — 소개, 기본 질문, 패턴, API, SDK. [시작 예제](https://docs.typesafe.ai/introduction/quickstart)부터 보라고 목록이 적는다.
- [Playground](projects/166-playground.md) — README.md:166 — 상태를 붙이고, 질문을 더하고, 타입이 있는 답을 브라우저에서 본다.
- [API keys](projects/167-api-keys.md) — README.md:167 — TypeSafe API 키 대시보드. 변수 이름은 `TYPESAFE_API_KEY`.
- [HTTP API reference](projects/168-http-api-reference.md) — README.md:168 — 호출 주소는 `POST https://api.typesafe.ai/v1/systemone`.
- [Models, prices, and limits](projects/169-models-prices-and-limits.md) — README.md:169 — 별칭, 버전, 속도 제한.
- [Workflow evals](projects/170-workflow-evals.md) — README.md:170 — 공개된 평가 방법과, 자동화 워크플로에서 모델별 결과.
- [GitHub org](projects/171-github-org.md) — README.md:171 — 공식 오픈소스 저장소라고 목록이 적는다. 이 스터디는 그 조직이 섞여 있는지를 여기서 다시 단정하지 않는다.
- [Agent skill](projects/172-agent-skill.md) — README.md:172 — Claude Code, Codex, 그 밖의 코딩 에이전트에 넣는 스킬. [typesafe-ai/skills](https://github.com/typesafe-ai/skills).
- [Jev 1.13 jaggedness](projects/173-jev-1-13-jaggedness.md) — README.md:173 — 지금 공개된 모델이 어디서 실패하는지.
- [Manifesto](projects/174-manifesto.md) — README.md:174 — 대화가 아니라 소프트웨어를 위해 만든, 기계가 바로 읽는 지능이라는 주장.
- [The Bitterest Lesson](projects/175-the-bitterest-lesson.md) — README.md:175 — 잘못된 과제를 최적화하면 규모에서 온 이득을 눌러 버릴 수 있다는 글.
- [AI: too good to be true, too bad to be useful](projects/176-ai-too-good-to-be-true-too-bad-to-be-usefu.md) — README.md:176 — 자동화에 선호도로 맞춘 채팅 모델을 쓰지 말자는 글.
- [Jev on Vercel AI Gateway](projects/177-jev-on-vercel-ai-gateway.md) — README.md:177 — AI SDK의 `experimental_evaluate`용으로 호스팅된 `typesafe-ai/jev`. 목록은 TypeSafe 대기 명단이 필요 없다고 적는다. 이 페이지의 가격은 여기서 확인하지 않았다.
- [Jev on Cloudflare Workers AI](projects/178-jev-on-cloudflare-workers-ai.md) — README.md:178 — `env.AI.run`으로 부르는 `typesafe/jev`. 지원 라우팅과 위험 상향의 예가 있다.

## 커뮤니티

- [Discord](projects/182-discord.md) — README.md:182 — Discord의 Show and Tell.
- [X @typesafeai](projects/183-x-typesafeai.md) — README.md:183 — X 계정 @typesafeai.
- [X @CompleteSkeptic](projects/184-x-completeskeptic.md) — README.md:184 — X 계정 @CompleteSkeptic. 창업자 Diogo Almeida.
- [LinkedIn](projects/185-linkedin.md) — README.md:185 — LinkedIn의 공지와 채용.

## 숫자가 붙은 빌드

- [Jev plays Doom](projects/193-jev-plays-doom.md) — README.md:193 — 게임 루프가 초당 약 10번 Jev에게 다음에 무엇을 할지 묻는다.
- [jev-ultrafast](projects/194-jev-ultrafast.md) — README.md:194 — Browser Use 에이전트에서 다음 행동을 고르는 자리를 Jev로 옮겼다.
- [Flight search with Browser Use](projects/195-flight-search-with-browser-use.md) — README.md:195 — 예약 흐름을 처음부터 끝까지 돌린다.
- [Stagehand on a remote browser](projects/196-stagehand-on-a-remote-browser.md) — README.md:196 — 브라우저 작업 한 건이 1센트의 10분의 1이라고 목록이 적는다.
- [jev-trader](projects/197-jev-trader.md) — README.md:197 — 300ms Monad 블록 안에서 사고팔기를 정한다. 주문창은 Kuru.
- [Triage across 1,500 emails](projects/198-triage-across-1-500-emails.md) — README.md:198 — 받은편지함 전체를 한 번에 분류한다. 제목은 메일 1,500통.
- [Every's editorial vibe check](projects/199-every-s-editorial-vibe-check.md) — README.md:199 — 문서 37개, 문서마다 질문 21개. 심어 둔 결함 7개 중 6개를 잡았다고 목록이 적는다.
- [1kpapers](projects/200-1kpapers.md) — README.md:200 — 말뭉치를 주제로 분류해 사이트로 공개했다.
- [Jev plays chess](projects/201-jev-plays-chess.md) — README.md:201 — 둘 수 있는 수를 Choice로 두고, 추론 모델과 비교한다.
- [3,282 posts, eight questions each](projects/202-3-282-posts-eight-questions-each.md) — README.md:202 — Ian Nuttall의 X 글 3,282개를 질문 여덟 개로 점수 매겨, 무엇이 다른 데로 옮겨 가는지 본다.
- [Post scoring with SuperX](projects/203-post-scoring-with-superx.md) — README.md:203 — 초고가 나가기 전에 질문 61개를 던진다.
- [724 competitor ads, broken down](projects/204-724-competitor-ads-broken-down.md) — README.md:204 — 광고 724개, 브랜드 37곳. 광고마다 훅, 형식, 제안, 클릭 유도 문구를 본다.
- [typesafe-computer-use](projects/205-typesafe-computer-use.md) — README.md:205 — macOS를 조작한다. 단계마다 타입이 있는 결정 하나.
- [jev-drone](projects/206-jev-drone.md) — README.md:206 — 하드웨어 위에서 나는 전술 판단 루프.
- [Wikiracing](projects/207-wikiracing.md) — README.md:207 — 수천 개 링크 가운데 하나를 고르고, 도착할 때까지 반복한다.

## SDK와 클라이언트

- [Python SDK](projects/217-python-sdk.md) — README.md:217 — `pip install typesafe-sdk`. [문서](https://docs.typesafe.ai/sdk/python).
- [JavaScript / TypeScript SDK](projects/218-javascript-typescript-sdk.md) — README.md:218 — `npm install @typesafe-ai/sdk`. [문서](https://docs.typesafe.ai/sdk/javascript).
- [System One adapter (Python)](projects/219-system-one-adapter-python.md) — README.md:219 — 같은 질문을 채팅 모델과 비교하려고, LLM API 뒤에 둔 `TypeSafeClient` 대체품. `pip install system-one-adapter`.
- [Vercel AI SDK provider](projects/220-vercel-ai-sdk-provider.md) — README.md:220 — `@ai-sdk/typesafe-ai`와 `experimental_evaluate`. `typeSafeAi.evaluationModel('jev-latest')` 또는 Gateway id `typesafe-ai/jev`.
- [jev-go](projects/224-jev-go.md) — README.md:224 — `go get github.com/Gaurav-Gosain/jev-go`. [Stumble/jev-go](https://github.com/Stumble/jev-go)도 있다. 의존성이 없고, TypeSafe 직접 호출과 Vercel AI Gateway 양쪽에서 되며, 대화형 CL...
- [typesafe_sdk](projects/225-typesafe-sdk.md) — README.md:225 — `system_one`과 모델 목록을 위한 Hex 패키지. [Jev (OTP)](https://github.com/dannote/jev)는 Jev를 GenServer 동료로 둔다. 답은 패턴 매칭하는 메시지로 오고, 네트워크 없는 테스트가 있다.
- [typesafe-sdk](projects/226-typesafe-sdk.md) — README.md:226 — Ruby 3.1 이상, 재시도, 스레드에 안전한 HTTP 풀. [RubyLLM TypeSafe](https://github.com/kieranklaassen/ruby_llm-typesafe)는 RubyLLM 2의 TypeSafe 제공자다. [typesafe-ai-rails](htt...
- [typesafe-ai-rs](projects/227-typesafe-ai-rs.md) — README.md:227 — 비동기 클라이언트와 블로킹 클라이언트. [Twister915/typesafe-ai](https://github.com/Twister915/typesafe-ai)는 재시도를 관찰할 수 있다. [typesafe-rs](https://github.com/AbdelStark/typesaf...
- [typesafe-sdk-php](projects/228-typesafe-sdk-php.md) — README.md:228 — 타입이 있는 DTO와 프로미스. [laravel-typesafe-jev](https://github.com/Butochnikov/laravel-typesafe-jev)는 Laravel 12/13 설정, 파사드, 범위가 있는 DI, 녹음용 가짜 구현이다.
- [jevclient](projects/229-jevclient.md) — README.md:229 — 비동기 클라이언트 `pip install jevclient`. 공식 SDK와는 따로다.
- [swift-typesafe](projects/230-swift-typesafe.md) — README.md:230 — Swift 6.4 클라이언트. Python SDK 0.6.0 API에 맞춰 두었고 Linux도 포함한다.
- [zio-typesafe-ai](projects/231-zio-typesafe-ai.md) — README.md:231 — noul·choice·score용 작은 DSL이 있는 ZIO 클라이언트.
- [typesafe-dotnet-sdk](projects/232-typesafe-dotnet-sdk.md) — README.md:232 — 타입이 있는 질문과, 확신이 붙은 답.
- [Advocaat](projects/233-advocaat.md) — README.md:233 — 확률, 선택, 점수에 태그 헬퍼가 있는 작은 클라이언트.
- [typesafe-on-neon](projects/234-typesafe-on-neon.md) — README.md:234 — Neon AI Gateway용 Neon Function 프록시.

## 브라우저·컴퓨터 조작

- [Jev Ultrafast](projects/242-jev-ultrafast.md) — README.md:242 — [Browser Use](https://github.com/browser-use)에서 나온 브라우저 에이전트. Jev가 한 요청에서 동작과 DOM 요소를 고르고, 작은 LLM은 `TYPE_TEXT`일 때만 글을 쓴다. Google Flights에서 취리히에서 런던까지 약 7초. 라...
- [Jev for Chrome](projects/243-jev-for-chrome.md) — README.md:243 — 비공식 Chrome 확장(Manifest V3)으로 Jev Ultrafast를 옮긴 것이다. Jev가 한 요청에서 동작과 DOM 요소를 고르고, 작은 텍스트 모델이 입력값을 쓴다. 사용자 탭에서 OpenRouter, TypeSafe, Cloudflare로 돈다. 헤드리스 Chrom...
- [jev-ego](projects/244-jev-ego.md) — README.md:244 — ego lite 위의 브라우저 에이전트. TypeSafe 요청 하나가 동작과 번호 매긴 요소를 고른다. 에이전트용 observe/act/suggest/step CLI가 있다.
- [jev-browser](projects/245-jev-browser.md) — README.md:245 — LLM이 결과를 계획하고, Jev가 Playwright 스냅샷에서 클릭과 입력을 정한다. 호출당 약 300ms라고 목록이 적는다. 라이브러리, CLI, MCP 서버로 나간다.
- [Jev Browser (Vlad Terin)](projects/246-jev-browser-vlad-terin.md) — README.md:246 — 에이전트 스킬과 런타임. Codex가 계획하고, Jev가 요소를 고르고, 실행기가 행동하고 단계를 확인한다. 이 주소는 2026-09-22에 404였다.
- [typesafe-computer-use](projects/247-typesafe-computer-use.md) — README.md:247 — macOS 조작 루프. 화면을 OCR하고, Jev가 다음 행동을 분류한 뒤 클릭한다. 단계당 약 $0.0002라고 목록이 적는다.
- [Mobile Jev](projects/248-mobile-jev.md) — README.md:248 — Mobilerun 위의 Android 에이전트. Jev가 탭을 정한다. Uber를 열어 SFO에서 골든게이트까지, 결제 화면까지 약 21초, 행동 9번. ADB는 없다.
- [Unclutter](projects/249-unclutter.md) — README.md:249 — Chrome·Firefox 확장. Jev가 페이지에서 없어도 되는 요소를 분류하고, 로컬 템플릿 규칙이 다음 방문에서 숨긴다.
- [TypeSafe AdBlock](projects/250-typesafe-adblock.md) — README.md:250 — Chrome 확장. Jev가 DOM 요소가 광고인지 판단해 지운다. 키는 사용자가 넣고 백엔드는 없다. 데모이지 실제 광고 차단기가 아니라고 목록이 적는다.
- [jev-skip](projects/251-jev-skip.md) — README.md:251 — 브라우저 확장. 유튜브 자막을 읽어 구간마다 협찬 확률을 탐색 막대에 칠한다. 인트로가 끝나기 전이고, 사람들이 모은 데이터베이스는 없다.
- [More agents and browsers on madewithjev.com](projects/253-more-agents-and-browsers-on-madewithjev-co.md) — README.md:253 — → [madewithjev.com의 에이전트와 브라우저](https://madewithjev.com/categories/agents-and-browsers)

## 검색·데이터

- [Every](projects/257-every.md) — README.md:257 — 의미로 코드를 찾는 CLI. 함수마다 예/아니오를 묻고, Noul 확률로 순위를 매긴다.
- [blink](projects/258-blink.md) — README.md:258 — 코드베이스 검색. 여러 워커가 Jev에게 어느 파일이 자연어 질문에 답하는지 묻는다.
- [Jev Search](projects/259-jev-search.md) — README.md:259 — 웹 검색. Choice와 Noul로 출처, 기간, 검색어 후보를 고른 뒤 Search1API로 가져온 결과를 순위를 매긴다. 데모는 [jev.s1.dev](https://jev.s1.dev).
- [neo4jev](projects/260-neo4jev.md) — README.md:260 — Neo4j 그래프 탐색. 노드마다 Jev가 따라갈 관계를 고르고, 로그 확률로 빔 탐색을 한다.
- [jev-bfs](projects/261-jev-bfs.md) — README.md:261 — 위키백과 문서 사이의 링크 경로를 찾는다. Jev가 각 페이지의 나가는 링크 순위를 매기고, 검색 제어는 Python이 한다.
- [hono-jev-router](projects/262-hono-jev-router.md) — README.md:262 — 실험용 Hono 라우터. Jev가 들어온 요청을 평범한 말로 적은 경로 설명에 맞춘다.
- [sqlite3-jev](projects/263-sqlite3-jev.md) — README.md:263 — SQLite C 확장. `jev_noul`, `jev_choice`, `jev_score`를 libcurl로 부르는 SQL 함수로 둔다.
- [jev-curate](projects/264-jev-curate.md) — README.md:264 — Rust로 만든 대량 합성 데이터 거름망. JSONL과 Parquet 행에 Noul 검사를 하고, 통과한 행과 버린 행을 디스크로 흘려 보낸다.
- [1kpapers](projects/265-1kpapers.md) — README.md:265 — 논문 1,018편을 주제로 분류해 둘러볼 수 있는 사이트로 냈다.
- [jev.nvim](projects/266-jev-nvim.md) — README.md:266 — Neovim 플러그인. Treesitter로 현재 버퍼를 함수 단위로 나누고, 함수마다 평범한 말로 물은 뒤, 확률 순으로 quickfix에 답을 올린다.
- [More research and data builds on madewithjev.com](projects/268-more-research-and-data-builds-on-madewithj.md) — README.md:268 — → [madewithjev.com의 연구와 데이터](https://madewithjev.com/categories/research-and-data)

## 개발 도구·코드 리뷰

- [Jev Review](projects/272-jev-review.md) — README.md:272 — 초점을 좁힌 Jev 호출로 돌리는 단계별 코드 리뷰와 로컬 대시보드.
- [Foreman](projects/273-foreman.md) — README.md:273 — 소프트웨어 공장 루프. Codex가 구현하고, Jev가 따로 완성도, 테스트, 사람이 필요한지를 판단한다.
- [Clean Code Judge](projects/274-clean-code-judge.md) — README.md:274 — PR 파일마다 Clean Code 냄새 31개를 예/아니오로 보고, 함수 크기와 중첩도 본다. 그 판정을 글을 쓰는 모델에 넘겨 산문으로 만든다.
- [OpenWork](projects/275-openwork.md) — README.md:275 — 평가 테스트킷에 Jev를 검증 심판으로 넣어, 에이전트가 만든 결과물을 타입이 있는 판정으로 막는다. OpenWork 스타 수는 Jev 채택 수가 아니다. 생성일은 2026-01-14.
- [jev-shell-history](projects/276-jev-shell-history.md) — README.md:276 — Fish처럼 보이는 zsh 자동 제안. 치는 동안 Jev가 최근 히스토리 순위를 매긴다.
- [jev-secret-detection](projects/277-jev-secret-detection.md) — README.md:277 — diff 안의 비밀을 찾고, Jev 판정을 반복할 수 있게 둔다.
- [commit-miner](projects/278-commit-miner.md) — README.md:278 — 커밋 diff를 분류하는 Rust CLI. 버그 수정, 보안과 CWE, 변경 종류. HTML과 CSV 보고.
- [Jev Logs](projects/279-jev-logs.md) — README.md:279 — OpenTelemetry 로그 분류. 비싼 LLM이 보관함을 보기 전에 Jev가 진단 가치와 우선순위를 점수로 매긴다.
- [typeful-triage](projects/280-typeful-triage.md) — README.md:280 — 여러 사람이 쓰는 이슈 분류 대시보드. 이슈마다 종류, 심각도, 긴급, 중복, 다음 단계가 고정된 질문이다. 사람이 고친 답은 다음 실행에서 모델에 다시 보여 준다.
- [jev-resilience](projects/281-jev-resilience.md) — README.md:281 — Spring WebFlux 스타터. HTTP 200인데 실패가 조용한 경우를 Jev로 잡는 의미 회로 차단기.
- [tripwire](projects/282-tripwire.md) — README.md:282 — AI SDK 미들웨어와 OpenAI 호환 프록시. LLM 응답마다 Jev 검사 일곱 번, 약 100ms, 확신으로 게이트를 연다.
- [ProgressGate](projects/283-progressgate.md) — README.md:283 — 에이전트 루프가 의미 없이 제자리인지를 본다. Jev가 궤적을 판단하고, 코드는 CONTINUE, WARN, REPLAN, HALT를 돌려준다.
- [jev-harness](projects/284-jev-harness.md) — README.md:284 — Jev 주위의 운영 층. 정책, 확신 게이트, 그림자 모드, 레시피, 평가 CLI.
- [jev-tree](projects/285-jev-tree.md) — README.md:285 — 분류 체계를 재귀 Choice로 내려가, 선택지 255개 상한보다 큰 목록도 넣는다.
- [Notra](projects/286-notra.md) — README.md:286 — 마케팅 분석. `NOTRA_JEV_CLASSIFIERS`가 브랜드 노출 분류를 LLM에서 떼어 Jev의 예/아니오 판단으로 보내고, 기준은 0.5, 목표는 p50 300ms라고 목록이 적는다. 이 스터디는 그 수치와 플래그를 소스에서 확인하지 않았다. 라이선스는 AGPL-3.0이라...
- [jev-eval-agent](projects/287-jev-eval-agent.md) — README.md:287 — 초기 Jev 시험을 위한 공개 평가 하네스.
- [Supercov](projects/288-supercov.md) — README.md:288 — 코딩 에이전트용 코드 품질과 테스트 커버리지. Jev가 소스 파일마다 점수를 매겨, 에이전트가 무엇을 먼저 고칠지 알게 한다.
- [jev-commit](projects/289-jev-commit.md) — README.md:289 — 커밋 전 훅. Jev 호출 한 번이 커밋 메시지가 스테이징된 diff와 맞는지, 디버그 찌꺼기와 적지 않은 작업이 있는지를 본다. 커밋을 막는 것은 자격 증명을 봤을 때뿐이다.

## 모델 라우팅

- [jev-router](projects/293-jev-router.md) — README.md:293 — Claude Code와 Codex의 턴마다 경로를 나눈다. 단순한 일은 빠른 층, 어려운 일은 강한 층. `npm i -g jev-router`.
- [jev-codex-router](projects/294-jev-codex-router.md) — README.md:294 — Codex 턴마다 경로를 나눈다. Jev가 모델, 생각의 깊이, 속도 모드를 고른다.
- [jev-router (prismhq)](projects/295-jev-router-prismhq.md) — README.md:295 — 오픈소스 LiteLLM 기반 라우터. Jev 결정이 요청마다 어느 모델이 받을지 고른다.
- [pi-jev-router](projects/296-pi-jev-router.md) — README.md:296 — Pi 코딩 에이전트의 요청마다 모델을 고른다. 결정은 Vercel AI Gateway 위의 Jev.
- [jcm-router](projects/297-jcm-router.md) — README.md:297 — 로컬 프록시. 메시지마다 Claude 모델과 추론 강도를 고르고, 캐시된 본 대화는 건드리지 않는다.
- [jev-agent-skill-router](projects/298-jev-agent-skill-router.md) — README.md:298 — 에이전트 스킬 선택을 타입이 있고 확신을 보는 결정으로 보낸다. 약한 일치는 찍지 않고 거절한다.

## 업무용 앱

- [typesafe-jev CV screener](projects/302-typesafe-jev-cv-screener.md) — README.md:302 — 이력서 폴더를 고칠 수 있는 정책에 비춘다. 정책이 바뀌면 후보를 다시 채점하는 비용은 없다고 목록이 적는다.
- [Jev email intent workflow](projects/303-jev-email-intent-workflow.md) — README.md:303 — 비동기 LangGraph 워크플로. 타입이 있는 Choice(`invoice` 또는 `general`)가 들어온 메일을 맞는 처리기로 보낸다.
- [HA-Jev](projects/304-ha-jev.md) — README.md:304 — Home Assistant 연동. 엔티티 상태에 대한 타입이 있는 질문이 센서와 자동화 동작이 된다. 사용량, 비용, 하루 예산 엔티티가 있다.
- [Jev Trader](projects/305-jev-trader.md) — README.md:305 — Kuru의 MON-USDC 주문창에서 Monad 블록마다 사고팔기 하나. 라이브는 [jev-trader.vercel.app](https://jev-trader.vercel.app/).
- [Human Compiler](projects/306-human-compiler.md) — README.md:306 — 회사 문장을 붙이면 Jev가 수동공격, 긴급, 정보 밀도를 점수로 매기고, 코드가 rustc 스타일 진단을 낸다. 라이브는 [human-compiler.asfarlab.fun](https://human-compiler.asfarlab.fun).
- [JEVMETER](projects/307-jevmeter.md) — README.md:307 — 아무 영상에나 얹는 라이브 Jev 미터. 문장마다 점수를 매겨 16:9 편집으로 그린다.
- [jev-audio-beeper](projects/308-jev-audio-beeper.md) — README.md:308 — 지연이 짧은 모욕 탐지기. Jev가 정하고, ffmpeg가 약 466ms 안에 삑 소리를 넣는다. 트랙의 나머지는 다시 쓰지 않는다.
- [Jev Moderation Bot](projects/309-jev-moderation-bot.md) — README.md:309 — Discord 봇. 들어온 메시지를 피싱, 스팸, 사회공학으로 점수를 매기고, 네 단계로 올린다.
- [citation-verifier](projects/310-citation-verifier.md) — README.md:310 — 인용한 논문이 그 문장을 받치는지 본다. Claude가 인용 위치를 찾고, Jev가 뒷받침 정도를 점수로 매기며, 마지막 판단은 사람이다.
- [LegalForecast-MTD](projects/311-legalforecast-mtd.md) — README.md:311 — 연방 각하 신청 판결을 Jev가 예측하는지 보는 벤치. 점수는 claim-defendant micro-Brier.
- [Smart home assistant demo](projects/312-smart-home-assistant-demo.md) — README.md:312 — 공식 대화형 데모. 한 호출에 질문을 많이 넣고, 코드가 관련 있는 답만 남긴다. LLM은 나누기와 잡담에만 쓴다.
- [SmartMoney-Cub](projects/313-smartmoney-cub.md) — README.md:313 — 실험용이고 읽기 전용인 매매 일지. 공시, 이벤트 전보, 중앙은행 문장을 Jev에 넘겨 증거와 정책 입장에 대한 Choice·Noul·Score를 받는다. 사람은 올리거나 거절하고, 주문은 내지 않는다.
- [Jev Web Analyzer](projects/314-jev-web-analyzer.md) — README.md:314 — 공개 SaaS 랜딩을 깨끗한 Markdown으로 보고, 첫 방문에서 이해되는지에 대한 `Choice` 열 개를 묻는다. 검증, 정책, 표현은 애플리케이션 코드에 남긴다.

## 로봇·하드웨어

- [Jev Drone](projects/318-jev-drone.md) — README.md:318 — MuJoCo 쿼드로터. 제어와 안전은 코드에 있고, Jev는 2.5Hz로 더 느린 전술 판단을 한다.
- [jev-askable-arm](projects/319-jev-askable-arm.md) — README.md:319 — 시뮬레이션 Franka 팔에 영어 목표를 처음 보는 문장으로 준다. Jev가 미리 적어 둔 기본 동작을 이어서 고른다.
- [robo-harness](projects/320-robo-harness.md) — README.md:320 — SO-101 팔 작업대. Jev 결정 실행기가 지출 한도 안에서, 타입이 있는 후보 동작 중 관절 이동을 고른다.
- [More robotics and devices on madewithjev.com](projects/322-more-robotics-and-devices-on-madewithjev-c.md) — README.md:322 — → [madewithjev.com의 로봇과 장치](https://madewithjev.com/categories/robotics-and-devices)

## 데모·게임

- [Yes / No](projects/328-yes-no.md) — README.md:328 — 가입 없는 무료 Noul 데모. 질문하면 예, 아니오, 아마도가 오고, 필요하면 웹 검색을 한다.
- [Jev Tetris](projects/329-jev-tetris.md) — README.md:329 — 구멍, 쌓인 높이, 울퉁불퉁함으로 회전과 열을 고른다.
- [Jev Pac-Man](projects/330-jev-pac-man.md) — README.md:330 — 미로를 JSON으로 두고, 갈림마다 Jev가 실시간으로 방향을 고른다.
- [typesafe-mario](projects/331-typesafe-mario.md) — README.md:331 — 구조화된 에뮬레이터 상태로 슈퍼 마리오 브라더스를 둔다.
- [jev-doom-agent](projects/332-jev-doom-agent.md) — README.md:332 — 브라우저 안의 Doom. Chocolate Doom WASM, 공간 상태, 라이브 결정 계측.
- [jev-gomoku](projects/333-jev-gomoku.md) — README.md:333 — MoonBit 클라이언트와 Jev 대 Jev 오목.
- [jev-t-rex-runner](projects/334-jev-t-rex-runner.md) — README.md:334 — Chrome 공룡 게임을 Jev가 한다.
- [snake-jev](projects/335-snake-jev.md) — README.md:335 — 뱀 게임. 한 판에 방향 결정이 수백 번. [typesafe-snake](https://github.com/sorrycc/typesafe-snake)도 있다.
- [Jev Plays StarCraft](projects/336-jev-plays-starcraft.md) — README.md:336 — 오리지널 스타크래프트 셰어웨어 캠페인을 구조화된 상태로 두는 하네스. 확인된 실행과 확률 추적이 있다.
- [Jev × Civilization II](projects/337-jev-civilization-ii.md) — README.md:337 — 브라우저 안의 오리지널 문명 2. Jev가 제국, 도시, 연구, 유닛 행동을 고른다. 실험용이고, 확인된 승리는 아직 없다고 목록이 적는다.
- [Jev Guard](projects/338-jev-guard.md) — README.md:338 — 댓글 검토를 시험하는 놀이터.
- [Hollow Creek](projects/339-hollow-creek.md) — README.md:339 — 마을 NPC가 잡담 대신 틱마다 당신을 판단한다.
- [Jev mood demo](projects/340-jev-mood-demo.md) — README.md:340 — 시간에 걸쳐 친절하게 또는 못되게 말한다. 구조화된 상태가 기분을 따라간다.
- [Jev Room](projects/341-jev-room.md) — README.md:341 — 문장 하나에서 방 설정 여섯 개. Jev가 고르고 앱이 그린다.
- [TypeSafe Typewriter](projects/342-typesafe-typewriter.md) — README.md:342 — Val Town 라이브 데모. 치는 동안 타입이 있는 판단 16개가 갱신된다.
- [got-jev](projects/343-got-jev.md) — README.md:343 — 왕좌의 게임 롤플레이. 이야기 모델이 장면을 쓰고, Jev는 존 스노가 어디 있는지, 위험이 얼마인지, 그 아래에 무엇이 깔려야 하는지를 답한다.
- [Little Airways](projects/344-little-airways.md) — README.md:344 — 장난감 군도 항공 관제. 우회, 비상, 누가 먼저 착륙하는지. 약 150ms.
- [jev-plays-pokemon-red](projects/345-jev-plays-pokemon-red.md) — README.md:345 — PyBoy 위의 포켓몬 레드. 경로와 계산은 코드가 갖고, Jev는 갈림에서만 고른다. 전투 턴마다 기절 예측을 남기고, RAM이 말한 결과와 Brier로 점수를 매긴다.
- [More games and real-time builds on madewithjev.com](projects/347-more-games-and-real-time-builds-on-madewit.md) — README.md:347 — → [madewithjev.com의 게임과 실시간](https://madewithjev.com/categories/games-and-real-time)

## 에이전트 도구·MCP

- [TypeSafe agent skill](projects/353-typesafe-agent-skill.md) — README.md:353 — 공식 스킬. 기본 질문, 패턴, 평가를 어떻게 짜는지. Claude Code는 `claude plugin marketplace add typesafe-ai/skills` 다음 `claude plugin install typesafe@typesafe-ai`. 다른 에이전트는 `npx...
- [eve](projects/354-eve.md) — README.md:354 — Vercel의 에이전트 프레임워크. 실험용 `autoModel`의 기본값은 Gateway `typesafe-ai/jev`이고, 허용 목록에서 언어 모델을 고른다.
- [AI CLI](projects/355-ai-cli.md) — README.md:355 — Vercel Labs CLI. `evaluate`의 평가 모델로 Jev를 돌릴 수 있다.
- [jev-mcp (jkudish)](projects/356-jev-mcp-jkudish.md) — README.md:356 — 쿡북 패턴 셋을 감싼 Node MCP. `jev_verify`는 인용 확인, `jev_screen`은 프롬프트 주입 가드, `jev_find`는 임베딩 없이 의미 순위. `npx -y github:jkudish/jev-mcp`.
- [jev-mcp (blakestone-x)](projects/357-jev-mcp-blakestone-x.md) — README.md:357 — Python MCP 서버. 분류, 점수, 확인, 맞추기, 거르기.
- [Jev Review MCP](projects/358-jev-review-mcp.md) — README.md:358 — 로컬 우선 MCP. Claude Code, Codex, Cursor, OpenCode가 쓰는 동안 Jev에게 구조화된 품질 리뷰를 받는다.
- [typesafe-mcp](projects/359-typesafe-mcp.md) — README.md:359 — Claude Desktop, Claude Code, Codex용 Go CLI와 단일 바이너리 MCP.
- [Jevbridge](projects/360-jevbridge.md) — README.md:360 — ACP/MCP 어댑터. Codex, Claude, Grok, OpenCode 옆에 타입이 있는 Jev 결정과 컴퓨터 조작을 둔다.
- [fast-jev-compaction](projects/361-fast-jev-compaction.md) — README.md:361 — Claude Code 플러그인과 npm 라이브러리. 문맥을 요약하는 대신 Jev가 도구 호출에 점수를 매겨 낡은 것을 버린다.
- [SkillRanker](projects/362-skillranker.md) — README.md:362 — Rust CLI. 지금 세션 문맥으로 다음 단계에 맞는 에이전트 스킬 순위를 Jev가 매긴다. Claude Code 훅이 있다.
- [pi-typesafe](projects/363-pi-typesafe.md) — README.md:363 — Pi 확장. 동의를 받고 키를 관리하는 TypeSafe 클라이언트 하나, 묶어서 부르는 `typesafe_evaluate`, 오프라인으로 시험할 수 있는 전송.
- [pi-jev](projects/364-pi-jev.md) — README.md:364 — Pi 확장. 그림자 모드의 도구 호출 게이트, 출력 심판, 타입이 있는 `jev_ask`.
- [pi-warden](projects/365-pi-warden.md) — README.md:365 — pi-typesafe 위의 Pi 가드. 대화 대신 붙잡아 둔 도구 결과. 쓰기는 프로젝트 규칙 파일에 비춘다.
- [pi-jev-auto-mode](projects/366-pi-jev-auto-mode.md) — README.md:366 — Pi 자동 모드. Jev가 `bash`, `write`, `edit`를 의미로 승인하고, 정하지 못하면 닫힌 채로 실패한다.
- [Bicameral](projects/367-bicameral.md) — README.md:367 — Pi 코딩 하네스. LLM이 쓰고, Jev가 정책, 루프 탐지, 리뷰에 타입이 있는 반사 행동을 준다. 샌드박스가 아니라고 분명히 적는다.
- [ask-jev-skill](projects/368-ask-jev-skill.md) — README.md:368 — Hermes 스킬. 에이전트에게 범위가 닫힌 결정이 필요할 때 Jev에게 묻는다.
- [jev-system-architect](projects/369-jev-system-architect.md) — README.md:369 — 잘 부러지는 의미 논리를 찾아 Choice, Score, Noul 경계로 바꾸는 스킬.
- [augustus](projects/370-augustus.md) — README.md:370 — 설계 판단 스킬. Choice·Score·Noul을 고전적 방법에 대응시키고, 합성 대수, 질문 설계 진단, 반증용 검증 게이트를 둔다.
- [jev-judgment](projects/371-jev-judgment.md) — README.md:371 — 코딩 에이전트의 닫힌 판단을 Jev로 보내, 판정이 타입이 있고 싸고 실행끼리 비교되게 하는 스킬.
- [pi-typesafe-jev](projects/372-pi-typesafe-jev.md) — README.md:372 — System One 판단을 Pi 도구 다섯 개로 연다. 임계값, 가중치, 행동은 코드와 사용자가 쥔다.
- [limpet](projects/373-limpet.md) — README.md:373 — Stop 훅. 평범한 말로 적은 완료 규칙을 Jev가 판단해, 에이전트가 너무 일찍 끝내지 못하게 한다.
- [jev-guard](projects/374-jev-guard.md) — README.md:374 — Claude Code, Codex, Pi, ACP 에이전트용 프롬프트 주입과 위험한 행동 가드.
- [dsh-auto-mode](projects/375-dsh-auto-mode.md) — README.md:375 — DeepSeek Harness 권한 프리셋. 끝 프롬프트 단계에서, 에이전트가 마지막 메시지에 남긴 열린 질문을 Jev가 답한다.
- [jev-belay](projects/376-jev-belay.md) — README.md:376 — Claude Code Stop 훅. 전사를 읽어 일이 끝났다는 증거가 있는지 본다. 파일이 바뀌었는데 그 뒤 통과한 검사가 없을 때만 질문 네 개의 Jev 호출을 한 번 쓰고 멈추게 한다. 오류 경로는 모두 열어 둔 채 실패한다.

## 업종별 용도

- [use-case map](projects/380-use-case-map.md) — README.md:380 — 분야를 가로질러 반복되는 결정의 모양. 각각은 작은 결정 시스템이다. 상태 객체, 원자 질문, 코드가 소유한 검토 분기. TypeSafe의 [용도 지도](https://docs.typesafe.ai/concepts/use-case-map)와 [워크플로 평가](https://eval...
- [Customer support](projects/384-customer-support.md) — README.md:384 — 의도를 분류하고, 긴급과 환불 의도를 보고, 불만을 점수로 매긴다. 경로는 일반 코드가 나누고, 확신이 낮은 티켓은 올린다.
- [Security operations](projects/385-security-operations.md) — README.md:385 — 경보를 자산 맥락, 권한과 붙인다. 그 활동이 무단인지 물은 뒤, 결정적인 플레이북이 닫거나, 대기열에 넣거나, 알리거나, 격리한다.
- [Finance and payments](projects/386-finance-and-payments.md) — README.md:386 — 송장을 발주서와 계약에 맞춘다. Jev는 중복, 사기, 잘못된 거래처 신호를 표시하고, 합계, 날짜, 실행은 코드가 가진다.
- [Insurance](projects/387-insurance.md) — README.md:387 — 청구 채점 기준을 독립된 Noul로 돌린다. 보장, 면책, 사기 징후. 가운데 구간은 사람 검토로 보낸다.
- [Legal and compliance](projects/388-legal-and-compliance.md) — README.md:388 — 계약, 신고, 마케팅 자료에서 빠진 조항, 금지된 주장, 정책 위반을 찾는다.
- [Recruiting](projects/389-recruiting.md) — README.md:389 — 직무와 관련된 증거를 평가하고, 후보를 역할에 맞추고, 지원서를 보내고, 불확실한 건은 올린다.
- [Sales and lead gen](projects/390-sales-and-lead-gen.md) — README.md:390 — 이상 고객 적합, 구매자 관련성, 아픔, 구매 의도를 점수로 매긴 뒤 리드를 보낸다.
- [E-commerce](projects/391-e-commerce.md) — README.md:391 — 상품 등록을 정규화하고, 속성을 뽑고, 위조나 금지 상품 신호를 보고, 예외를 보낸다.
- [Moderation and trust & safety](projects/392-moderation-and-trust-safety.md) — README.md:392 — 조직 기준을 독성, 스팸, 사기, 개인정보 노출에 적용한다. 불확실이라는 결과가 명시되어 있다.
- [Advertising](projects/393-advertising.md) — README.md:393 — 브랜드 안전, 청중 적합성, 규제 표현, 광고와 랜딩의 일치를 본다.
- [Gaming](projects/394-gaming.md) — README.md:394 — 채팅을 검토하고, 몰입이나 좌절을 점수로 매기고, 악용과 이탈 신호를 보고, 플레이어 지원으로 보낸다.
- [Financial crime](projects/395-financial-crime.md) — README.md:395 — 거래 서술과 KYC 자료를 평가한다. 엔티티를 맞추고 조사 대기열의 우선순위를 정한다.
- [Scientific discovery](projects/396-scientific-discovery.md) — README.md:396 — 논문을 거르고, 질적 연구의 주제를 표시하고, 원고 인용을 확인하고, 엔티티를 증거에 연결한다.
- [Risk and forecasting](projects/397-risk-and-forecasting.md) — README.md:397 — 사고 보고와 거래 서술을, 지도 학습 모델이 쓸 확률적 특성으로 바꾼다.
- [Knowledge graphs](projects/398-knowledge-graphs.md) — README.md:398 — 엔티티 종류와 관계를 분류하고, 모순을 보고, 확률적 탐색을 받친다.
- [Support inbox triage](projects/402-support-inbox-triage.md) — README.md:402 — 한 호출에 의도, 긴급, 심각도, 불만 질문을 펼친다. 확신 있는 답은 실행하고 나머지는 보낸다.
- [RAG passage filtering](projects/403-rag-passage-filtering.md) — README.md:403 — 답하는 모델이 보기 전에 구절마다 관련성, 모순, 주입 위험을 점수로 매긴다.
- [LLM guardrails](projects/404-llm-guardrails.md) — README.md:404 — 프롬프트, 답, 도구 호출을 위험 Noul과 해악 Score로 거른다. 정책이 통과, 검토, 차단을 정한다.
- [Confidence-gated actions](projects/405-confidence-gated-actions.md) — README.md:405 — 되돌릴 수 있는 읽기 전용은 문턱을 낮추고, 위험한 작업은 높인다. 나머지는 사람.
- [Model routing](projects/406-model-routing.md) — README.md:406 — 빠른 타입이 있는 결정이, 결정적 코드, 싼 LLM, 앞선 LLM, 사람 가운데 고르게 한다.
- [Structured extraction cascades](projects/407-structured-extraction-cascades.md) — README.md:407 — 작은 모델이 후보 필드를 뽑고, Jev가 값마다 확인하고, 실패한 것만 추론 모델로 올린다.
- [Composite scoring](projects/408-composite-scoring.md) — README.md:408 — 독립된 차원을 점수로 매긴 뒤, 코드가 가진 가중치로 합친다. 리드, 후보, 벤더, 위험.
- [Corpus map-reduce](projects/409-corpus-map-reduce.md) — README.md:409 — 모든 문서에 같은 질문을 한다. 논문 1,018편, 글 3,282개, 광고 724개, 메일 1,500통. 문서가 아니라 합계를 읽는다.
- [Real-time control](projects/410-real-time-control.md) — README.md:410 — 마감이 프레임, 블록, 틱이면 코드가 가능한 행동을 만들고 Jev가 하나를 고른다.

## 패턴

- [Speculative fan-out](projects/416-speculative-fan-out.md) — README.md:416 — 적용되지 않을 수 있는 질문까지 많이 묻고, 걸러내는 일은 코드가 한다.
- [Confidence-gated routing](projects/417-confidence-gated-routing.md) — README.md:417 — 답은 무엇인지이고, 확신은 행동할지이다.
- [Composite scoring](projects/418-composite-scoring.md) — README.md:418 — 원자 점수와, 코드가 가진 가중치.
- [Intent routing](projects/419-intent-routing.md) — README.md:419 — 분류한 뒤 로직, 전문 LLM, 사람에게 넘긴다.
- [How to build with System One](projects/421-how-to-build-with-system-one.md) — README.md:421 — 같이 볼 것: [System One으로 만드는 법](https://docs.typesafe.ai/concepts/how-to-build-with-system-one), [용도 지도](https://docs.typesafe.ai/concepts/use-case-map), [확신](h...
- [confidence](projects/421-confidence.md) — README.md:421 — 같이 볼 것: [System One으로 만드는 법](https://docs.typesafe.ai/concepts/how-to-build-with-system-one), [용도 지도](https://docs.typesafe.ai/concepts/use-case-map), [확신](h...

## 따라 하는 예제

- [console cookbooks](projects/425-console-cookbooks.md) — README.md:425 — 공식이고, 붙여 넣어 쓰는 워크플로. 전체 색인: [콘솔 쿡북](https://console.typesafe.ai/docs/cookbooks)과 [문서 색인](https://docs.typesafe.ai/llms.txt).
- [docs index](projects/425-docs-index.md) — README.md:425 — 공식이고, 붙여 넣어 쓰는 워크플로. 전체 색인: [콘솔 쿡북](https://console.typesafe.ai/docs/cookbooks)과 [문서 색인](https://docs.typesafe.ai/llms.txt).
- [Parallel questions](projects/427-parallel-questions.md) — README.md:427 — 한 `state`에 질문을 많이 묶는다. N번이 아니라 호출 한 번.
- [Line-by-line search](projects/428-line-by-line-search.md) — README.md:428 — 줄 id 수백 개를 질의에 대해 점수로 매긴다. Choice와, 답이 있는지 묻는 Noul.
- [Re-ranking](projects/429-re-ranking.md) — README.md:429 — BM25로 짧게 고른 뒤, 질의와 후보 쌍마다 TypeSafe 질문 하나.
- [Guardrails for LLMs](projects/430-guardrails-for-llms.md) — README.md:430 — LLM에 들어가고 나오는 메시지를 거른다. 확률 문턱은 코드에 둔다.
- [Double-checking citations](projects/431-double-checking-citations.md) — README.md:431 — 인용 문맥이 주장을 받치는지. 확신이 사람 검토의 문을 연다.
- [Classifying RAG passages](projects/432-classifying-rag-passages.md) — README.md:432 — 답하는 모델 전에, 가져온 구절을 남기거나, 표시하거나, 버린다.
- [Function calling](projects/433-function-calling.md) — README.md:433 — 자연어 요청을, 인자가 닫힌 집합인 보통의 타입이 있는 함수에 대응시킨다.
- [Skill suggestion](projects/434-skill-suggestion.md) — README.md:434 — 에이전트 스킬 목록의 순위를 매긴 뒤 위쪽 몇 개만 읽는다.
- [Hierarchical classification](projects/435-hierarchical-classification.md) — README.md:435 — Choice 확률로 깊은 분류 체계를 빔 탐색한다.
- [SDE cascade](projects/436-sde-cascade.md) — README.md:436 — 구조화 데이터 추출을 두 단계로 잇는다. 작은 모델, 확인, 추론 모델.
- [Date extraction](projects/437-date-extraction.md) — README.md:437 — 이름이 있는 날짜 조각을 묻고, 해석과 검증은 코드가 한다.
- [Pre-parsed value extraction](projects/438-pre-parsed-value-extraction.md) — README.md:438 — 정규식이 후보를 만들고, Jev가 요청된 구간을 고른다.
- [Knowledge graph entity alignment](projects/439-knowledge-graph-entity-alignment.md) — README.md:439 — 합칠지, 연결하지 않은 채 둘지, 큐레이터에게 보낼지를 점수로 매긴다.
- [Autoresearch feature discovery](projects/440-autoresearch-feature-discovery.md) — README.md:440 — 지도 학습 모델의 숫자 특성으로 쓸 TypeSafe 질문을 제안한다.
- [Classification using confidence](projects/441-classification-using-confidence.md) — README.md:441 — 확신이 높을 때만 가는 라벨을 보고, 아니면 위 단계로 올라간다.
- [Structure recovery](projects/442-structure-recovery.md) — README.md:442 — 서식이 빠진 평문에서 Markdown을 다시 만든다.
- [Self-consistency: nouls](projects/443-self-consistency-nouls.md) — README.md:443 — 불확실한 확률은 검토로 보내되, 원값은 숨기지 않는다.
- [Jev Cookbook](projects/444-jev-cookbook.md) — README.md:444 — 커뮤니티 쿡북. 실행 가능한 Node 레시피 15개. 티켓, 표 행, 문서, 송장, 메일을 `state`로 넘기고, 한 호출에 Choice·Noul·Score를 묻는다. 문턱, 검토 구간, 행동은 코드에 남긴다. 레시피 본문은 복사하지 않았다.

## 벤치마크

- [Workflow evals](projects/450-workflow-evals.md) — README.md:450 — 공식. 자동화 워크플로 네 개. 건마다 정확도, 비용, 시간. Jev와 앞선 모델.
- [typesafe-ai-benchmark](projects/451-typesafe-ai-benchmark.md) — README.md:451 — 같은 System One 질문에서 Jev와 Cerebras 위의 Qwen 3.8 27B.
- [Jev Rerank Bench](projects/452-jev-rerank-bench.md) — README.md:452 — 재순위 비교. 제공자 원문 응답, 채점 코드, 불확실 구간.
- [Jev Spam Eval](projects/453-jev-spam-eval.md) — README.md:453 — 학습된 TF-IDF 기준선과 견준 제로샷 스팸 연구. 사후 조정에 대한 단서가 있다.
- [Jev Phishing Bench](projects/454-jev-phishing-bench.md) — README.md:454 — 메일 2,000통. 클릭할지 말지에서 Jev와 Claude Haiku 4.5. 보정, 지연, 비용. 여기서 정확도는 Haiku가 이긴다고 목록이 적는다.
- [jev-agent-failure-benchmark](projects/455-jev-agent-failure-benchmark.md) — README.md:455 — Who&When Pro, 주입된 에이전트 실패. 누가, 어느 단계, 오류 종류에서 Jev와 강한 LLM.
- [jev-sec-bench](projects/456-jev-sec-bench.md) — README.md:456 — 공개 말뭉치에서 눈을 가린 프롬프트 주입과 취약 코드 탐지 벤치.
- [Jev DSPy Lab](projects/457-jev-dspy-lab.md) — README.md:457 — DSPy 동반 도구. TypeSafe 호출을 기록하고 재생하면서 보정, 선택적 위험, 기권, 지연, 비용을 잰다.
- [jevcal](projects/458-jevcal.md) — README.md:458 — CLI. 자기 라벨 데이터에서 목표 정확도에 맞는 질문별 확신 문턱을 맞추고, Jev 업데이트가 잠근 문턱을 깨면 CI를 실패시킨다.
- [ASSAY-001](projects/459-assay-001.md) — README.md:459 — Banking77과 CLINC150에서 Jev 보정과 타입 안전을 사전 등록해 본 독립 확인. 판정은 갈리고, 로그는 전부 있다. [기록](https://donttrustme.ai/assay-001.html).
- [Jev search rerank eval](projects/460-jev-search-rerank-eval.md) — README.md:460 — 라벨이 있는 쌍 9,831개. Jev 재순위 대 BM25와 bge-m3. 합치면 이기고, Jev 혼자서는 임베딩을 이기지 못한다고 목록이 적는다.
- [Smoking-history extraction benchmark](projects/461-smoking-history-extraction-benchmark.md) — README.md:461 — 합성 노트 1,000개. 정확도, 비용, 지연에서 Jev와 OpenAI 구조화 출력.
- [Jev Playground](projects/462-jev-playground.md) — README.md:462 — 상태가 명시된 게임에서, 검증된 합법 수를 고르는 일로 Jev를 Luna, Haiku, Gemini와 견준다.
- [jev-research-eval](projects/463-jev-research-eval.md) — README.md:463 — Jev Ultrafast의 연구용 브라우저 과제를 위한 재현 가능한 평가 하네스와 현장 노트.

## 연구·오픈 모델

- [jevlike](projects/469-jevlike.md) — README.md:469 — 문맥과 텍스트 선택지 N개를 선택지별 확률로 보내는 작은 한 패스 채점기를 학습한다. Doom·체스 비전 데모와 Wikispeedia 예. TypeSafe의 구조나 RLCD를 재현한 것이 아니라고 분명히 적는다.
- [openjev](projects/470-openjev.md) — README.md:470 — 집의 RTX 3090에서 Jev 비슷한 것을 돌릴 수 있나. 글을 생성하지 않고 선택지 로짓을 읽는다. [zhihz/openjev](https://github.com/zhihz/openjev)는 따로인 로컬 프리뷰로, 두 언어의 확률 질문에 답한다.
- [PocketJev](projects/471-pocketjev.md) — README.md:471 — 아이폰에서 MLX와 Qwen3-VL 선택지 로짓으로 보는 결정. 카메라와 선택지 3개, 글 생성 없음, 약 1초, 사진은 저장하지 않는다.
- [jev-visual](projects/472-jev-visual.md) — README.md:472 — Apple Silicon에서 Jev처럼 보이는 시각 추론을 가르치는 예. 공유된 멀티모달 문맥, 후보 채점, 분류 공장·Breakout·제스처 데모.
- [jevmlx](projects/473-jevmlx.md) — README.md:473 — Apple Silicon의 아무 MLX 모델에나 Jev식 병렬 제약 결정. 한 번의 순전파로 스키마에 맞는 JSON.
- [JEVfire](projects/474-jevfire.md) — README.md:474 — vLLM으로 CUDA LLM에 Jev에서 영감을 받은 병렬 결정. 브라우저 마리오 데모, 로컬에서 행동당 약 71ms.
- [decider](projects/475-decider.md) — README.md:475 — Qwen3.5-2B 미세조정. 한 패스에 보정된 확률이 붙은 타입이 있는 결정을 낸다.
- [Parallel Constrained Decoding (Qwen2.5-1B-RLCD)](projects/476-parallel-constrained-decoding-qwen2-5-1b-r.md) — README.md:476 — 오픈소스 RLCD식 병렬 제약 디코딩을 보는 Hugging Face 스페이스.
- [eve-rlcd](projects/477-eve-rlcd.md) — README.md:477 — Jev에서 영감을 받은 0.6B 결정 모델. 맞고 틀림 피드백만으로 강화학습한다. 보상은 결과에서 말한 확률을 뺀 값. 한 `state` 위에서 Choice·Score·Noul을 병렬로 답하고 글을 생성하지 않는다. RLVR 제거 실험과 [공개 가중치](https://hugging...

## 기사

- [TypeSafe AI debuts model for machines that plays Doom](projects/481-typesafe-ai-debuts-model-for-machines-that.md) — README.md:481 — The Register의 공개 보도.
- [Mini-Vibe Check: TypeSafe's Jev Judged Everything I've Written in 0.7 Seconds](projects/482-mini-vibe-check-typesafe-s-jev-judged-ever.md) — README.md:482 — Every의 Mike Taylor가 자기 글 모음에 Jev를 돌렸다. 판단 1,709번이 1센트 미만이라고 목록이 적는다.
- [Building a harness with Jev](projects/483-building-a-harness-with-jev.md) — README.md:483 — LangChain이 모델 경로와, 위험한 도구 호출을 타입이 있는 결정 뒤에 두는 이야기.
- [Jev, from a developer's angle](projects/484-jev-from-a-developer-s-angle.md) — README.md:484 — Flavio Copes. 분류, RAG 거르기, 인용 확인, 확신 게이트.
- [Jev, Sorted](projects/485-jev-sorted.md) — README.md:485 — 공개 주장이 1차 자료를 읽어 보면 무엇이 남고, 무엇이 아직 벤더 보고인지.
- [TypeSafe Jev played chess (and landed next to reasoning models)](projects/486-typesafe-jev-played-chess-and-landed-next-.md) — README.md:486 — Maxim Saplin이 체스를 둘 수 있는 수의 Choice로 제한한다.
- [Jev: one judge call, or twelve dimension scores?](projects/487-jev-one-judge-call-or-twelve-dimension-sco.md) — README.md:487 — 분류 과제 세 개에서 따로 잰 측정. 토큰 비용과 거짓 양성 비율.
- [Testing Jev on public and private data: classifier or filter?](projects/488-testing-jev-on-public-and-private-data-cla.md) — README.md:488 — 호출 16,000번. gpt-5.4-mini, gpt-5.6-luna와 비교. 어디서 이기고 어디서 깨지는지, 문턱을 정하는 절차.
- [Jev vs Mistral and Gemini for event validation](projects/489-jev-vs-mistral-and-gemini-for-event-valida.md) — README.md:489 — 지역 행사 목록을 검증하는 맞대결.
- [TypeSafeのJevを正しく驚く、それってLLMでできませんか？](projects/490-typesafe-jev-llm.md) — README.md:490 — 일본어 글. JSON 대 로짓 지름길을 Gemma에서 재현하고, 공개 마리오 하네스에서 Jev와 LLM을 비교한다. 이 스터디는 그 원문을 번역하지 않았고, 목록의 영어 한 줄만 옮겼다.
- [jev 同士に五目並べで対戦させた](projects/491-jev.md) — README.md:491 — 일본어 글. 소스와 시간 기록이 있는 Jev 대 Jev 오목. 이 스터디는 그 원문을 번역하지 않았고, 목록의 영어 한 줄만 옮겼다.
- [Jev on AI Wiki](projects/492-jev-on-ai-wiki.md) — README.md:492 — 커뮤니티가 유지하는 참조 페이지.

## 토론·소셜

- [Introducing System One Models and Jev](projects/496-introducing-system-one-models-and-jev.md) — README.md:496 — 점수 1,800의 Hacker News 공개 스레드. 벤치마크를 의심하는 읽기는 여기에 있다.
- [Launch thread by Diogo Almeida](projects/497-launch-thread-by-diogo-almeida.md) — README.md:497 — TypeSafe 창업자가, RLCD로 학습한 결정 모델이 채팅 모델보다 경제 가치로 가는 더 짧은 길이라고 말한다.
- [TypeSafe AI releases Jev (r/singularity)](projects/498-typesafe-ai-releases-jev-r-singularity.md) — README.md:498 — Reddit은 Jev를, 채팅이 아니라 소프트웨어를 위한 환각이 낮고 싼 결정 모델로 그린다.
- [Testing Jev for Pi extensions (r/PiCodingAgent)](projects/499-testing-jev-for-pi-extensions-r-picodingag.md) — README.md:499 — Jev를 에이전트 도구 사용의 안전층으로 쓰는 사람들.
- [Jev "playing" Minecraft (r/accelerate)](projects/500-jev-playing-minecraft-r-accelerate.md) — README.md:500 — 진행 중인 데모. 밤에 좀비를 피하는 장면이 있다.
- [Model router built with Jev](projects/501-model-router-built-with-jev.md) — README.md:501 — 요청을 넘기기 전에 Jev가 어느 모델이 받을지 정한다.
- [MLP on Qwen 4B mimicking Jev](projects/502-mlp-on-qwen-4b-mimicking-jev.md) — README.md:502 — Qwen 4B 위의 작은 MLP가 Jev 같은 결정 행동을 재현한다.
- [Running a local TypeSafe Jev](projects/503-running-a-local-typesafe-jev.md) — README.md:503 — 일본어 글. 로컬에서 Jev식 결정 모델을 시도한다. 이 스터디는 그 원문을 번역하지 않았고, 목록의 영어 한 줄만 옮겼다.
- [Jev as an AI agent safety monitor](projects/504-jev-as-an-ai-agent-safety-monitor.md) — README.md:504 — 에이전트 행동을 먼저 검사하면 공격의 대부분을 잡고 잘못된 차단은 거의 없다고 한다. 그 수치는 이 스터디가 재지 않았다.
- [Rethinking security engineering with Jev](projects/505-rethinking-security-engineering-with-jev.md) — README.md:505 — 보안 일 가운데 순수하게 공학적인 결정은 채팅 모델이 아니라 Jev 몫이라는 주장.
- [Ask Jev anything, it will judge](projects/506-ask-jev-anything-it-will-judge.md) — README.md:506 — Convex로 받친 공개 데모. 판단할 질문 백만 개를 청한다.
- [First Jev use case in a Mac app](projects/507-first-jev-use-case-in-a-mac-app.md) — README.md:507 — 출시된 Mac 앱이, 언어 모델이 로드되지 않았을 때 설정과 문제 해결 질문을 Jev로 보낸다.
- [Jev 中文解读](projects/508-jev.md) — README.md:508 — 중국어 글. System One을, 코드가 쓰는 보정된 타입이 있는 결정 층으로 설명한다. 이 스터디는 그 원문을 번역하지 않았고, 목록의 영어 한 줄만 옮겼다.
- [Launch roundup](projects/509-launch-roundup.md) — README.md:509 — 브라우저, 논문, 메일, 매매, 게임을 한 스레드에 모은 정리.

## 자주 묻는 질문

- [FAQ: What is Jev?](projects/515-faq-what-is-jev.md) — README.md:515 — Jev는 TypeSafe AI의 모델이고, 목록은 2026-09-15 얼리 액세스에 나왔다고 한다. 첫 System One 모델이다. 글을 생성하는 대신 타입이 있는 질문(Choice, Score, Noul)을 상태에 비춰 평가하고, 보정된 확률이 붙은 구조화된 답을 돌려준다. 7...
- [FAQ: What is TypeSafe AI?](projects/519-faq-what-is-typesafe-ai.md) — README.md:519 — TypeSafe AI는 샌프란시스코의 AI 랩이고, 창업자는 전에 OpenAI에서 지시 따르기 방법을 다룬 Diogo Almeida다. 목록은 회사가 $40M을 모았고, 사람과 대화하는 모델이 아니라 소프트웨어가 소비하는 기계 고유의 지능을 한다고 적는다. $40M은 그날 받아 온...
- [FAQ: Is Jev an LLM?](projects/523-faq-is-jev-an-llm.md) — README.md:523 — 아니다. 자연어를 읽지만 글을 생성하지 않는다. 답의 공간은 질문이 미리 정하므로, 출력은 구성상 타입에 맞고 준 공간 밖의 값을 지어낼 수 없다. 목록 안의 앵커는 [Jev vs LLM](#jev-vs-llm).
- [FAQ: What is RLCD?](projects/527-faq-what-is-rlcd.md) — README.md:527 — Reinforcement Learning for Calibrated Decisions. System One 모델을 위한 TypeSafe의 학습 방법. RLHF가 사람이 선호하는 응답을 최적화할 때, RLCD는 인식적으로 정직한 확률의 결정을 최적화한다. 확신이 높으면 정확도도 높아...
- [FAQ: How much does Jev cost?](projects/531-faq-how-much-does-jev-cost.md) — README.md:531 — 입력 100만 토큰당 $0.042. 출력 토큰은 무료. 전형적인 타입이 있는 질문은 1센트의 아주 작은 조각이라, 위의 대표 빌드가 판단 1,709번을 1센트 미만으로 적는다고 목록이 말한다.
- [FAQ: How do I get access?](projects/535-faq-how-do-i-get-access.md) — README.md:535 — 길이 셋이다. [typesafe.ai](https://typesafe.ai) 얼리 액세스 대기 명단, [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev)(모델 id `typesafe-ai/jev`, 목록은 대기 명단이 없다...
- [FAQ: What are Jev's limits?](projects/539-faq-what-are-jev-s-limits.md) — README.md:539 — Choice는 선택지 255개까지. 텍스트만이고 이미지, 오디오, 비디오는 없다. 적은 속도 제한은 초당 250,000토큰, 분당 1,200요청이며 TypeSafe는 동적으로 바뀔 수 있다고 한다. 현재 모델의 알려진 실패는 [Jev 1.13 들쭉날쭉](https://docs.ty...
- [FAQ: What is a System One model?](projects/543-faq-what-is-a-system-one-model.md) — README.md:543 — 소프트웨어 안에서 빠르고 구조화된 결정을 위해 만든 모델 종류를 TypeSafe가 부르는 이름. 사람에게 글을 생성하는 채팅 모델과 대비된다. 빠르고 직관적인 System 1 사고에서 이름을 땄다. Jev가 첫 공개 모델이다.

## 다른 목록

- [awesome-jev (AnotiaWang)](projects/547-awesome-jev-anotiawang.md) — README.md:547 — Jev 응용, 라이브러리, 자료를 모은 커뮤니티 목록. 영어와 간체 중국어.
- [awesome-jev (yibie)](projects/548-awesome-jev-yibie.md) — README.md:548 — 응용 분야별로 정리한 Jev 프로젝트와 토론.
- [awesome-jev (cobanov)](projects/549-awesome-jev-cobanov.md) — README.md:549 — 출처가 달린 Jev 프로젝트 목록. 결정 분야별로 정렬.
- [awesome-jev-by-typesafe (Anil-matcha)](projects/550-awesome-jev-by-typesafe-anil-matcha.md) — README.md:550 — 근거가 달린 용도, 패턴, 시작 코드.
- [awesome-jev-typesafe (valentynkit)](projects/551-awesome-jev-typesafe-valentynkit.md) — README.md:551 — CC0이고 awesome-lint를 통과했다. 무엇을 설치할지 기준으로 정렬하고, 만들기 전에 알 한계를 짧게 적는다.
- [typesafe-ai on PyPI](projects/552-typesafe-ai-on-pypi.md) — README.md:552 — 커뮤니티 리다이렉트 심. 실제 패키지는 `typesafe-sdk`. 슬롭스쿼팅을 막으려고 등록했다.

## 라이선스

- [CONTRIBUTING.md](projects/556-contributing-md.md) — README.md:556 — [CONTRIBUTING.md](CONTRIBUTING.md)를 본다. 짧게는, 프로젝트에 링크와 한 줄 설명을 더하는 풀 리퀘스트를 연다. 쓸모 있고, 흥미롭고, 실제로 Jev 위에 지었거나 그 인터페이스에서 분명히 영감을 받아야 한다. 실험이거나 드라이런만 하는 경로(매매, 홈...
- [CC0 1.0](projects/562-cc0-1-0.md) — README.md:562 — [CC0 1.0](LICENSE). 이 목록은 퍼블릭 도메인에 둔다. 그 기부는 목록 문장에 미치고, 링크된 코드에는 미치지 않는다.
