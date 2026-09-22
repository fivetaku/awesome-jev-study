# Catalog

[한국어](../ko/catalog.md) · [English](../en/catalog.md)

Each page has the list sentence, the checked facts, the role Jev plays, the setup, an LLM counterfactual, and a script counterfactual.

282 pages. No source trace.


## front

- [Submit yours →](projects/018-submit-yours.md) — README.md:18 — The submit page takes one link. The page says Jev reads it, decides whether it belongs, and sorts it. Listings are free, and the page says nobody can pay for...
- [madewithjev.com](projects/018-madewithjev-com.md) — README.md:18 — madewithjev.com is a directory of what people are building with Jev. The list says every build carries the cost, latency, and source the author reported.

## What is Jev?

- [Choice](projects/064-choice.md) — README.md:64 — Pick one option from a list
- [Score](projects/065-score.md) — README.md:65 — Rate the state on a rubric
- [Noul](projects/066-noul.md) — README.md:66 — Is this statement true?

## Jev vs LLM

- [Jev vs LLM 표](projects/074-jev-vs-llm.md) — README.md:74 — The list's table (README.md:74-85), which it attributes to the launch post. Existing LLMs versus System One + Jev: RLHF or RLVR versus RLCD, strings that nee...

## Pricing, limits, and access

- [가격·한도 표](projects/091-item.md) — README.md:91 — The list's price table (README.md:91-100), a snapshot it dates September 18, 2026. `jev-latest` is `jev-1.13.0`. Endpoint `POST https://api.typesafe.ai/v1/sy...
- [typesafe.ai](projects/099-typesafe-ai.md) — README.md:99 — Early access via waitlist at [typesafe.ai](https://typesafe.ai)
- [Vercel AI Gateway](projects/100-vercel-ai-gateway.md) — README.md:100 — [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev) (`typesafe-ai/jev`) and [Cloudflare Workers AI](https://developers.cloudflare.com/ai/models/typ...

## Quick start

- [퀵스타트 예제](projects/102-item.md) — README.md:102 — The list's quick start (README.md:102-159), not executed here. Python `pip install typesafe-sdk`, classes `Choice`, `Noul`, `Score`, `TypeSafeClient.system_o...

## Official resources

- [TypeSafe AI](projects/163-typesafe-ai.md) — README.md:163 — Company homepage, waitlist, and product overview.
- [Introducing System One Models and Jev](projects/164-introducing-system-one-models-and-jev.md) — README.md:164 — Launch post by founder Diogo Almeida: architecture, RLCD, pricing, Doom and Wikiracing demos, FAQ.
- [Documentation](projects/165-documentation.md) — README.md:165 — Introduction, primitives, patterns, API, and SDKs. Start with the [quick start](https://docs.typesafe.ai/introduction/quickstart).
- [Playground](projects/166-playground.md) — README.md:166 — Paste a state, add questions, see typed answers in the browser.
- [API keys](projects/167-api-keys.md) — README.md:167 — Dashboard for TypeSafe API keys (`TYPESAFE_API_KEY`).
- [HTTP API reference](projects/168-http-api-reference.md) — README.md:168 — `POST https://api.typesafe.ai/v1/systemone`.
- [Models, prices, and limits](projects/169-models-prices-and-limits.md) — README.md:169 — Aliases, versions, and rate limits.
- [Workflow evals](projects/170-workflow-evals.md) — README.md:170 — Published eval methodology and per-model results on automation workflows.
- [GitHub org](projects/171-github-org.md) — README.md:171 — Official open-source repositories.
- [Agent skill](projects/172-agent-skill.md) — README.md:172 — Drop-in skill for Claude Code, Codex, and other coding agents ([typesafe-ai/skills](https://github.com/typesafe-ai/skills)).
- [Jev 1.13 jaggedness](projects/173-jev-1-13-jaggedness.md) — README.md:173 — Known failure modes of the current public model.
- [Manifesto](projects/174-manifesto.md) — README.md:174 — The case for machine-native intelligence built for software, not conversation.
- [The Bitterest Lesson](projects/175-the-bitterest-lesson.md) — README.md:175 — Why optimizing the wrong task can dominate gains from scale.
- [AI: too good to be true, too bad to be useful](projects/176-ai-too-good-to-be-true-too-bad-to-be-usefu.md) — README.md:176 — Against preference-optimized chat models for automation.
- [Jev on Vercel AI Gateway](projects/177-jev-on-vercel-ai-gateway.md) — README.md:177 — Hosted `typesafe-ai/jev` for the AI SDK's `experimental_evaluate`, no TypeSafe waitlist required.
- [Jev on Cloudflare Workers AI](projects/178-jev-on-cloudflare-workers-ai.md) — README.md:178 — `typesafe/jev` via `env.AI.run`, with worked support-routing and risk-escalation examples.

## Community

- [Discord](projects/182-discord.md) — README.md:182 — Official TypeSafe server; builder demos live in Show and Tell.
- [X @typesafeai](projects/183-x-typesafeai.md) — README.md:183 — Product and research updates.
- [X @CompleteSkeptic](projects/184-x-completeskeptic.md) — README.md:184 — Founder Diogo Almeida.
- [LinkedIn](projects/185-linkedin.md) — README.md:185 — Company announcements and hiring.

## Featured builds with real numbers

- [Jev plays Doom](projects/193-jev-plays-doom.md) — README.md:193 — Game loop asking Jev what to do ~10 times a second
- [jev-ultrafast](projects/194-jev-ultrafast.md) — README.md:194 — Browser Use's agent with the next-action decision moved to Jev
- [Flight search with Browser Use](projects/195-flight-search-with-browser-use.md) — README.md:195 — Booking flow driven end to end
- [Stagehand on a remote browser](projects/196-stagehand-on-a-remote-browser.md) — README.md:196 — Browser tasks at a tenth of a cent each
- [jev-trader](projects/197-jev-trader.md) — README.md:197 — Buy/sell decided inside a 300 ms Monad block, on Kuru's order book
- [Triage across 1,500 emails](projects/198-triage-across-1-500-emails.md) — README.md:198 — A full inbox sorted in one pass
- [Every's editorial vibe check](projects/199-every-s-editorial-vibe-check.md) — README.md:199 — 37 documents, 21 questions each; 6 of 7 planted defects caught
- [1kpapers](projects/200-1kpapers.md) — README.md:200 — A corpus classified by topic and published as a site
- [Jev plays chess](projects/201-jev-plays-chess.md) — README.md:201 — Legal moves as a Choice, compared with reasoning models
- [3,282 posts, eight questions each](projects/202-3-282-posts-eight-questions-each.md) — README.md:202 — Ian Nuttall's X back catalogue scored for what travels
- [Post scoring with SuperX](projects/203-post-scoring-with-superx.md) — README.md:203 — 61 questions about a draft before it ships
- [724 competitor ads, broken down](projects/204-724-competitor-ads-broken-down.md) — README.md:204 — Hook, format, offer, CTA per ad across 37 brands
- [typesafe-computer-use](projects/205-typesafe-computer-use.md) — README.md:205 — macOS computer use, one typed decision per step
- [jev-drone](projects/206-jev-drone.md) — README.md:206 — Tactical judgment loop flying on hardware
- [Wikiracing](projects/207-wikiracing.md) — README.md:207 — Pick one link out of thousands until you arrive

## SDKs and clients

- [Python SDK](projects/217-python-sdk.md) — README.md:217 — `pip install typesafe-sdk`. [Docs](https://docs.typesafe.ai/sdk/python).
- [JavaScript / TypeScript SDK](projects/218-javascript-typescript-sdk.md) — README.md:218 — `npm install @typesafe-ai/sdk`. [Docs](https://docs.typesafe.ai/sdk/javascript).
- [System One adapter (Python)](projects/219-system-one-adapter-python.md) — README.md:219 — Drop-in `TypeSafeClient` replacement backed by LLM APIs, to compare Jev against chat models on the same questions. `pip install system-one-adapter`.
- [Vercel AI SDK provider](projects/220-vercel-ai-sdk-provider.md) — README.md:220 — `@ai-sdk/typesafe-ai` with `experimental_evaluate`; use `typeSafeAi.evaluationModel('jev-latest')` or the Gateway id `typesafe-ai/jev`.
- [jev-go](projects/224-jev-go.md) — README.md:224 — `go get github.com/Gaurav-Gosain/jev-go`. Also [Stumble/jev-go](https://github.com/Stumble/jev-go) - dependency-free, works against TypeSafe direct and Verce...
- [typesafe_sdk](projects/225-typesafe-sdk.md) — README.md:225 — Hex package for `system_one` and model listing. Also [Jev (OTP)](https://github.com/dannote/jev) - Jev as a peer GenServer; answers arrive as messages you pa...
- [typesafe-sdk](projects/226-typesafe-sdk.md) — README.md:226 — Ruby 3.1+, retries, thread-safe pooled HTTP. Also [RubyLLM TypeSafe](https://github.com/kieranklaassen/ruby_llm-typesafe) - TypeSafe provider for RubyLLM 2. ...
- [typesafe-ai-rs](projects/227-typesafe-ai-rs.md) — README.md:227 — async and blocking client. Also [Twister915/typesafe-ai](https://github.com/Twister915/typesafe-ai) - observable retries; [typesafe-rs](https://github.com/Ab...
- [typesafe-sdk-php](projects/228-typesafe-sdk-php.md) — README.md:228 — typed DTOs and promises. Plus [laravel-typesafe-jev](https://github.com/Butochnikov/laravel-typesafe-jev) - Laravel 12/13 config, facade, scoped DI, and a re...
- [jevclient](projects/229-jevclient.md) — README.md:229 — async client (`pip install jevclient`), separate from the official SDK.
- [swift-typesafe](projects/230-swift-typesafe.md) — README.md:230 — Swift 6.4 client aligned with the Python SDK 0.6.0 API, including Linux.
- [zio-typesafe-ai](projects/231-zio-typesafe-ai.md) — README.md:231 — ZIO client with a small DSL for noul / choice / score.
- [typesafe-dotnet-sdk](projects/232-typesafe-dotnet-sdk.md) — README.md:232 — typed questions and confidence-scored answers.
- [Advocaat](projects/233-advocaat.md) — README.md:233 — small client with tagged helpers for chances, choices, and scores.
- [typesafe-on-neon](projects/234-typesafe-on-neon.md) — README.md:234 — Neon Function proxy for the Neon AI Gateway.

## Browser and computer-use agents

- [Jev Ultrafast](projects/242-jev-ultrafast.md) — README.md:242 — Browser agent from [Browser Use](https://github.com/browser-use). Jev picks an operation and a DOM element in one request; a small LLM writes text only for `...
- [Jev for Chrome](projects/243-jev-for-chrome.md) — README.md:243 — Unofficial Chrome extension (Manifest V3) port of Jev Ultrafast: Jev picks the operation and DOM element in one request, a small text model writes typed valu...
- [jev-ego](projects/244-jev-ego.md) — README.md:244 — Browser agent on ego lite: one TypeSafe request picks operation + indexed element; agent-facing observe/act/suggest/step CLI.
- [jev-browser](projects/245-jev-browser.md) — README.md:245 — An LLM plans the outcome, Jev decides each click/type on a Playwright snapshot (~300 ms/call). Ships as a library, CLI, and MCP server.
- [Jev Browser (Vlad Terin)](projects/246-jev-browser-vlad-terin.md) — README.md:246 — Agent skill + runtime: Codex plans, Jev selects elements, a runner acts and verifies each step.
- [typesafe-computer-use](projects/247-typesafe-computer-use.md) — README.md:247 — macOS computer-use loop: OCR the screen, Jev classifies the next action, then click. About $0.0002/step.
- [Mobile Jev](projects/248-mobile-jev.md) — README.md:248 — Android agent on Mobilerun: Jev decides each tap. Opens Uber, SFO → Golden Gate, payment screen in ~21 s / 9 actions. No ADB.
- [Unclutter](projects/249-unclutter.md) — README.md:249 — Chrome / Firefox extension: Jev classifies nonessential page elements; local template rules hide them on later visits.
- [TypeSafe AdBlock](projects/250-typesafe-adblock.md) — README.md:250 — Chrome extension: Jev judges whether a DOM element is an ad and removes it. BYOK, no backend; a demo, not a real ad blocker.
- [jev-skip](projects/251-jev-skip.md) — README.md:251 — Browser extension that reads a YouTube video's caption track and paints a per-segment sponsor probability on the seek bar before the intro ends, with no crow...
- [More agents and browsers on madewithjev.com](projects/253-more-agents-and-browsers-on-madewithjev-co.md) — README.md:253 — → [More agents and browsers on madewithjev.com](https://madewithjev.com/categories/agents-and-browsers)

## Search, retrieval, and data

- [Every](projects/257-every.md) — README.md:257 — Semantic code-search CLI: a yes/no question against every function, ranked by Noul probability.
- [blink](projects/258-blink.md) — README.md:258 — Codebase search: an ensemble of walkers asks Jev which file answers a natural-language query.
- [Jev Search](projects/259-jev-search.md) — README.md:259 — Web search app using Choice and Noul judgments to select sources, time ranges, and query candidates, then rank results retrieved through Search1API. Live dem...
- [neo4jev](projects/260-neo4jev.md) — README.md:260 — Neo4j graph navigation: at each node Jev chooses which relationship to follow, with beam search over log-probabilities.
- [jev-bfs](projects/261-jev-bfs.md) — README.md:261 — Finds link paths between Wikipedia articles; Jev ranks each page's outgoing links while Python controls the search.
- [hono-jev-router](projects/262-hono-jev-router.md) — README.md:262 — Experimental Hono router: Jev matches an incoming request to a plain-language route description.
- [sqlite3-jev](projects/263-sqlite3-jev.md) — README.md:263 — SQLite C extension: `jev_noul` / `jev_choice` / `jev_score` as SQL functions via libcurl.
- [jev-curate](projects/264-jev-curate.md) — README.md:264 — High-throughput synthetic dataset sifter in Rust: Noul checks on JSONL and Parquet rows, streaming clean and rejected rows to disk.
- [1kpapers](projects/265-1kpapers.md) — README.md:265 — 1,018 papers classified by topic and published as a browsable site.
- [jev.nvim](projects/266-jev-nvim.md) — README.md:266 — Neovim plugin that splits the current buffer into functions with Treesitter, asks Jev a plain-language question against each one, and lists the answers in th...
- [More research and data builds on madewithjev.com](projects/268-more-research-and-data-builds-on-madewithj.md) — README.md:268 — → [More research and data builds on madewithjev.com](https://madewithjev.com/categories/research-and-data)

## Developer tools and code review

- [Jev Review](projects/272-jev-review.md) — README.md:272 — Staged code-review workflow and local dashboard driven by focused Jev calls.
- [Foreman](projects/273-foreman.md) — README.md:273 — Software-factory loop: Codex implements; Jev independently judges completeness, tests, and whether a human is needed.
- [Clean Code Judge](projects/274-clean-code-judge.md) — README.md:274 — Scores every PR file on 31 boolean Clean Code smells plus function size and nesting, then hands verdicts to a writing model for prose.
- [OpenWork](projects/275-openwork.md) — README.md:275 — Wires Jev into its eval testkit as a verification judge so agent-produced work is gated by typed verdicts.
- [jev-shell-history](projects/276-jev-shell-history.md) — README.md:276 — Fish-style zsh autosuggestions: Jev ranks recent history as you type.
- [jev-secret-detection](projects/277-jev-secret-detection.md) — README.md:277 — Secret-in-diff detector with repeatable Jev verdicts.
- [commit-miner](projects/278-commit-miner.md) — README.md:278 — Rust CLI that classifies commit diffs: bug fixes, security/CWEs, and change types. HTML/CSV reports.
- [Jev Logs](projects/279-jev-logs.md) — README.md:279 — OpenTelemetry log triage: Jev scores diagnostic value and priority before an expensive LLM looks at the archive.
- [typeful-triage](projects/280-typeful-triage.md) — README.md:280 — Multiplayer issue-triage dashboard: fixed typed questions per issue (kind, severity, urgency, duplicate, next step), with human corrections shown back to the...
- [jev-resilience](projects/281-jev-resilience.md) — README.md:281 — Spring WebFlux starter: a semantic circuit breaker that uses Jev to catch silent HTTP 200 failures.
- [tripwire](projects/282-tripwire.md) — README.md:282 — AI SDK middleware and OpenAI-compatible proxy: seven Jev checks on every LLM response in ~100 ms, confidence-gated.
- [ProgressGate](projects/283-progressgate.md) — README.md:283 — Detects semantic stagnation in agent loops: Jev judges the trajectory; code returns CONTINUE / WARN / REPLAN / HALT.
- [jev-harness](projects/284-jev-harness.md) — README.md:284 — Production layer around Jev: policy, confidence gate, shadow mode, recipes, and an eval CLI.
- [jev-tree](projects/285-jev-tree.md) — README.md:285 — Recursive Choice over a taxonomy so catalogs larger than Jev's 255-option cap still fit.
- [Notra](projects/286-notra.md) — README.md:286 — Marketing analytics: its `NOTRA_JEV_CLASSIFIERS` flag routes brand-visibility classifiers off an LLM and onto Jev boolean decisions at a 0.5 threshold, targe...
- [jev-eval-agent](projects/287-jev-eval-agent.md) — README.md:287 — Public eval harness for early Jev tests.
- [Supercov](projects/288-supercov.md) — README.md:288 — Code quality and test coverage for coding agents: Jev scores each source file so the agent knows what to fix first.
- [jev-commit](projects/289-jev-commit.md) — README.md:289 — Pre-commit hook where one Jev call judges whether the commit message matches the staged diff, checks for debug leftovers and unmentioned work, and blocks the...

## Model routing

- [jev-router](projects/293-jev-router.md) — README.md:293 — Per-turn routing for Claude Code and Codex: simple work to the fast tier, hard work to the strong tier. `npm i -g jev-router`.
- [jev-codex-router](projects/294-jev-codex-router.md) — README.md:294 — Per-turn Codex routing: Jev picks model, thinking depth, and speed mode.
- [jev-router (prismhq)](projects/295-jev-router-prismhq.md) — README.md:295 — Open-source LiteLLM-based router where a Jev decision picks which model serves each request.
- [pi-jev-router](projects/296-pi-jev-router.md) — README.md:296 — Automatic per-request model routing for the Pi coding agent through Jev decisions on Vercel AI Gateway.
- [jcm-router](projects/297-jcm-router.md) — README.md:297 — Local proxy that picks the Claude model and reasoning effort per message while leaving the cached main chat untouched.
- [jev-agent-skill-router](projects/298-jev-agent-skill-router.md) — README.md:298 — Routes agent skill selection through typed, confidence-aware decisions so weak matches are declined instead of guessed.

## Business and vertical apps

- [typesafe-jev CV screener](projects/302-typesafe-jev-cv-screener.md) — README.md:302 — Screens a folder of CVs against an editable policy; re-scoring candidates is free when the policy changes.
- [Jev email intent workflow](projects/303-jev-email-intent-workflow.md) — README.md:303 — Async LangGraph workflow: a typed Choice (`invoice` or `general`) routes each inbound email to the matching handler.
- [HA-Jev](projects/304-ha-jev.md) — README.md:304 — Home Assistant integration: typed questions about entity state become sensors and automation actions, with usage, cost, and daily-budget entities.
- [Jev Trader](projects/305-jev-trader.md) — README.md:305 — One buy/sell decision per Monad block on Kuru's MON-USDC book. Live demo: [jev-trader.vercel.app](https://jev-trader.vercel.app/).
- [Human Compiler](projects/306-human-compiler.md) — README.md:306 — Paste corporate prose; Jev scores passive-aggression, urgency, and information density, then code emits rustc-style diagnostics. Live: [human-compiler.asfarl...
- [JEVMETER](projects/307-jevmeter.md) — README.md:307 — Live Jev meter on any video: every sentence scored, rendered as a 16:9 edit.
- [jev-audio-beeper](projects/308-jev-audio-beeper.md) — README.md:308 — Low-latency audio insult detector: Jev decides, ffmpeg beeps in ~466 ms without rewriting the rest of the track.
- [Jev Moderation Bot](projects/309-jev-moderation-bot.md) — README.md:309 — Discord bot scoring incoming messages for phishing, spam, and social engineering, with a four-stage escalation ladder.
- [citation-verifier](projects/310-citation-verifier.md) — README.md:310 — Checks whether each cited paper actually supports the sentence citing it: Claude locates the quote, Jev scores the support, a human makes the final call.
- [LegalForecast-MTD](projects/311-legalforecast-mtd.md) — README.md:311 — Benchmark that asks Jev to predict federal motion-to-dismiss rulings, scored with claim-defendant micro-Brier metrics.
- [Smart home assistant demo](projects/312-smart-home-assistant-demo.md) — README.md:312 — Official interactive demo of speculative fan-out: many questions in one call, code keeps the relevant answers, LLM only for splits and chit-chat.
- [SmartMoney-Cub](projects/313-smartmoney-cub.md) — README.md:313 — Experimental, read-only trading journal that passes filings, event wires and central-bank statements to Jev for typed Choice, Noul and Score answers on evide...
- [Jev Web Analyzer](projects/314-jev-web-analyzer.md) — README.md:314 — Product evaluation: evaluates a public SaaS landing page as clean Markdown with ten bounded Jev `Choice` questions about first-visit understanding, leaving v...

## Robotics and hardware

- [Jev Drone](projects/318-jev-drone.md) — README.md:318 — MuJoCo quadrotor: control and safety stay in code; Jev handles slower tactical judgments at 2.5 Hz.
- [jev-askable-arm](projects/319-jev-askable-arm.md) — README.md:319 — Zero-shot English goals on a simulated Franka arm; Jev chains hardcoded primitives.
- [robo-harness](projects/320-robo-harness.md) — README.md:320 — SO-101 arm workbench: a Jev decision runner picks bounded joint steps from typed candidate actions under a spend budget.
- [More robotics and devices on madewithjev.com](projects/322-more-robotics-and-devices-on-madewithjev-c.md) — README.md:322 — → [More robotics and devices on madewithjev.com](https://madewithjev.com/categories/robotics-and-devices)

## Demos and games

- [Yes / No](projects/328-yes-no.md) — README.md:328 — Free no-signup Noul demo. Ask a question, get yes / no / maybe, with web search when needed.
- [Jev Tetris](projects/329-jev-tetris.md) — README.md:329 — Jev picks rotation and column from holes, stack height, and bumpiness.
- [Jev Pac-Man](projects/330-jev-pac-man.md) — README.md:330 — Maze as JSON; Jev picks the turn at each junction in realtime.
- [typesafe-mario](projects/331-typesafe-mario.md) — README.md:331 — Super Mario Bros. from structured emulator state.
- [jev-doom-agent](projects/332-jev-doom-agent.md) — README.md:332 — Browser-native Doom with Chocolate Doom WASM, spatial state, and live decision telemetry.
- [jev-gomoku](projects/333-jev-gomoku.md) — README.md:333 — MoonBit client plus Jev-vs-Jev gomoku.
- [jev-t-rex-runner](projects/334-jev-t-rex-runner.md) — README.md:334 — The Chrome dinosaur game, played by Jev.
- [snake-jev](projects/335-snake-jev.md) — README.md:335 — Snake: hundreds of typed direction decisions per run. Also [typesafe-snake](https://github.com/sorrycc/typesafe-snake).
- [Jev Plays StarCraft](projects/336-jev-plays-starcraft.md) — README.md:336 — Structured-state harness for the original StarCraft shareware campaign, with verified run and probability traces.
- [Jev × Civilization II](projects/337-jev-civilization-ii.md) — README.md:337 — Original Civ II in a browser; Jev chooses empire, city, research, and unit actions. Experimental; no verified win yet.
- [Jev Guard](projects/338-jev-guard.md) — README.md:338 — Comment-moderation playground.
- [Hollow Creek](projects/339-hollow-creek.md) — README.md:339 — Village NPCs that *judge* you each tick instead of chatting.
- [Jev mood demo](projects/340-jev-mood-demo.md) — README.md:340 — Talk nicely or nastily over time; structured state tracks mood.
- [Jev Room](projects/341-jev-room.md) — README.md:341 — One sentence → six room settings. Jev chooses, the app renders.
- [TypeSafe Typewriter](projects/342-typesafe-typewriter.md) — README.md:342 — Live Val Town demo: 16 typed judgments update as you type.
- [got-jev](projects/343-got-jev.md) — README.md:343 — Game of Thrones roleplay: a story model writes the scene; Jev answers where Jon Snow is, how much danger, and what should play under it.
- [Little Airways](projects/344-little-airways.md) — README.md:344 — Toy archipelago air-traffic control: divert / emergency / who lands first, ~150 ms.
- [jev-plays-pokemon-red](projects/345-jev-plays-pokemon-red.md) — README.md:345 — Pokemon Red on PyBoy where code owns the route and the arithmetic, Jev picks only at branches, and every battle turn logs a faint prediction scored by Brier ...
- [More games and real-time builds on madewithjev.com](projects/347-more-games-and-real-time-builds-on-madewit.md) — README.md:347 — → [More games and real-time builds on madewithjev.com](https://madewithjev.com/categories/games-and-real-time)

## Agent tools and MCP servers

- [TypeSafe agent skill](projects/353-typesafe-agent-skill.md) — README.md:353 — Official skill: primitives, patterns, and how to structure evaluations. Claude Code: `claude plugin marketplace add typesafe-ai/skills` then `claude plugin i...
- [eve](projects/354-eve.md) — README.md:354 — Vercel's agent framework. Experimental `autoModel` defaults to Gateway `typesafe-ai/jev` to pick a language model from an allowlist.
- [AI CLI](projects/355-ai-cli.md) — README.md:355 — Vercel Labs CLI that can run Jev as the evaluation model for its `evaluate` command.
- [jev-mcp (jkudish)](projects/356-jev-mcp-jkudish.md) — README.md:356 — Node MCP wrapping three cookbook patterns: `jev_verify` (citation check), `jev_screen` (prompt-injection guardrails), `jev_find` (semantic ranking without em...
- [jev-mcp (blakestone-x)](projects/357-jev-mcp-blakestone-x.md) — README.md:357 — Python MCP server: classify, score, check, match, and screen tools.
- [Jev Review MCP](projects/358-jev-review-mcp.md) — README.md:358 — Local-first MCP: Claude Code, Codex, Cursor, and OpenCode get structured quality review from Jev while they write.
- [typesafe-mcp](projects/359-typesafe-mcp.md) — README.md:359 — Go CLI and single-binary MCP for Claude Desktop, Claude Code, and Codex.
- [Jevbridge](projects/360-jevbridge.md) — README.md:360 — ACP/MCP adapter: typed Jev decisions and computer use beside Codex, Claude, Grok, and OpenCode.
- [fast-jev-compaction](projects/361-fast-jev-compaction.md) — README.md:361 — Claude Code plugin and npm library: Jev scores tool calls and drops stale ones instead of summarizing context.
- [SkillRanker](projects/362-skillranker.md) — README.md:362 — Rust CLI: Jev ranks which agent skill fits the next step from live session context, with Claude Code hooks.
- [pi-typesafe](projects/363-pi-typesafe.md) — README.md:363 — Pi extension: one consented, key-managed TypeSafe client, batched `typesafe_evaluate`, offline-testable transport.
- [pi-jev](projects/364-pi-jev.md) — README.md:364 — Pi extension with a shadow-mode tool-call gate, output judge, and typed `jev_ask`.
- [pi-warden](projects/365-pi-warden.md) — README.md:365 — Pi guardrails on pi-typesafe: held tool results instead of a dialog; write checks against a project rules file.
- [pi-jev-auto-mode](projects/366-pi-jev-auto-mode.md) — README.md:366 — Pi auto mode: Jev semantically approves `bash` / `write` / `edit`, and fails closed when it cannot decide.
- [Bicameral](projects/367-bicameral.md) — README.md:367 — Pi coding harness: LLM writes, Jev supplies typed reflexes for policy, loop detection, and review. Explicitly not a sandbox.
- [ask-jev-skill](projects/368-ask-jev-skill.md) — README.md:368 — Hermes skill: ask Jev whenever the agent needs a bounded decision.
- [jev-system-architect](projects/369-jev-system-architect.md) — README.md:369 — Skill that hunts for brittle semantic logic and turns it into Choice / Score / Noul boundaries.
- [augustus](projects/370-augustus.md) — README.md:370 — Design-judgment skill: maps Choice/Score/Noul onto classical methods with a composition algebra, question-design diagnosis, and falsifying validation gates.
- [jev-judgment](projects/371-jev-judgment.md) — README.md:371 — Agent skill that sends closed coding-agent judgments to Jev so verdicts stay typed, cheap, and comparable across runs.
- [pi-typesafe-jev](projects/372-pi-typesafe-jev.md) — README.md:372 — Exposes System One judgments as five Pi tools; code and users keep control of thresholds, weights, and actions.
- [limpet](projects/373-limpet.md) — README.md:373 — Stop hook that keeps an agent from finishing too early by judging plain-language completion rules with Jev.
- [jev-guard](projects/374-jev-guard.md) — README.md:374 — Prompt-injection and dangerous-action guard for Claude Code, Codex, Pi, and ACP agents.
- [dsh-auto-mode](projects/375-dsh-auto-mode.md) — README.md:375 — DeepSeek Harness permission preset whose end-prompt step has Jev answer the open questions an agent leaves in its final message.
- [jev-belay](projects/376-jev-belay.md) — README.md:376 — Claude Code Stop hook that reads the transcript for evidence of a completed task and, only when files changed with no passing check since, spends one four-qu...

## Use cases by industry

- [use-case map](projects/380-use-case-map.md) — README.md:380 — Decision shapes that recur across domains. Each is a small decision system: a state object, atomic questions, and a code-owned review branch. Expanded from T...
- [Customer support](projects/384-customer-support.md) — README.md:384 — Classify intent, detect urgency and refund intent, score frustration; route with ordinary code and escalate low-confidence tickets.
- [Security operations](projects/385-security-operations.md) — README.md:385 — Join an alert with asset context and authorizations; ask whether the activity is unauthorized, then let a deterministic playbook close, queue, notify, or con...
- [Finance and payments](projects/386-finance-and-payments.md) — README.md:386 — Match invoices against POs and contracts; Jev flags duplicate/fraud/wrong-vendor signals while code owns totals, dates, and execution.
- [Insurance](projects/387-insurance.md) — README.md:387 — Run a claims rubric as independent Nouls — coverage, exclusions, fraud indicators — and map the middle band to human review.
- [Legal and compliance](projects/388-legal-and-compliance.md) — README.md:388 — Find missing clauses, prohibited claims, and policy violations in contracts, filings, and marketing material.
- [Recruiting](projects/389-recruiting.md) — README.md:389 — Evaluate job-related evidence, match candidates to roles, route applications, escalate uncertain cases.
- [Sales and lead gen](projects/390-sales-and-lead-gen.md) — README.md:390 — Score ICP fit, buyer relevance, pain points, and purchase intent before routing leads.
- [E-commerce](projects/391-e-commerce.md) — README.md:391 — Normalize listings, extract product attributes, detect counterfeit or prohibited-listing signals, route exceptions.
- [Moderation and trust & safety](projects/392-moderation-and-trust-safety.md) — README.md:392 — Apply org-specific criteria to toxicity, spam, fraud, and personal-data exposure, with an explicit uncertain outcome.
- [Advertising](projects/393-advertising.md) — README.md:393 — Check brand safety, audience suitability, regulatory claims, and ad-to-landing-page alignment.
- [Gaming](projects/394-gaming.md) — README.md:394 — Moderate chat, score engagement or frustration, detect abuse and churn signals, route player support.
- [Financial crime](projects/395-financial-crime.md) — README.md:395 — Evaluate transaction narratives and KYC material; match entities and prioritize investigator queues.
- [Scientific discovery](projects/396-scientific-discovery.md) — README.md:396 — Screen papers, label themes in qualitative research, check manuscript citations, link entities to evidence.
- [Risk and forecasting](projects/397-risk-and-forecasting.md) — README.md:397 — Turn incident reports and transaction descriptions into probabilistic features for a supervised model.
- [Knowledge graphs](projects/398-knowledge-graphs.md) — README.md:398 — Classify entity types and relationships, detect contradictions, support probabilistic traversal.
- [Support inbox triage](projects/402-support-inbox-triage.md) — README.md:402 — Fan out intent, urgency, severity, and frustration questions in one call; act on the confident answers, route the rest.
- [RAG passage filtering](projects/403-rag-passage-filtering.md) — README.md:403 — Score relevance, contradiction, and injection risk per passage before the answering model sees it.
- [LLM guardrails](projects/404-llm-guardrails.md) — README.md:404 — Screen prompts, replies, and tool calls with hazard Nouls and a harm Score; policy passes, reviews, or blocks.
- [Confidence-gated actions](projects/405-confidence-gated-actions.md) — README.md:405 — Lower thresholds for reversible read-only actions, higher ones for risky operations, humans for the rest.
- [Model routing](projects/406-model-routing.md) — README.md:406 — Let a fast typed decision choose between deterministic code, a cheap LLM, a frontier LLM, or a person.
- [Structured extraction cascades](projects/407-structured-extraction-cascades.md) — README.md:407 — A small model extracts candidate fields; Jev verifies each value; only failures escalate to a reasoning model.
- [Composite scoring](projects/408-composite-scoring.md) — README.md:408 — Score independent dimensions, then combine with weights you own in code — leads, candidates, vendors, risk.
- [Corpus map-reduce](projects/409-corpus-map-reduce.md) — README.md:409 — Ask the same questions of every document: 1,018 papers, 3,282 posts, 724 ads, 1,500 emails. Read the aggregate, not the documents.
- [Real-time control](projects/410-real-time-control.md) — README.md:410 — When the deadline is a frame, a block, or a tick, code generates legal actions and Jev picks one.

## Patterns

- [Speculative fan-out](projects/416-speculative-fan-out.md) — README.md:416 — Ask many questions, including ones that may not apply; filter in code.
- [Confidence-gated routing](projects/417-confidence-gated-routing.md) — README.md:417 — The answer is *what*; confidence is *whether to act*.
- [Composite scoring](projects/418-composite-scoring.md) — README.md:418 — Atomic scores, weights you own in code.
- [Intent routing](projects/419-intent-routing.md) — README.md:419 — Classify, then hand off to logic, a specialist LLM, or a human.
- [How to build with System One](projects/421-how-to-build-with-system-one.md) — README.md:421 — See also: [How to build with System One](https://docs.typesafe.ai/concepts/how-to-build-with-system-one), the [use-case map](https://docs.typesafe.ai/concept...
- [confidence](projects/421-confidence.md) — README.md:421 — See also: [How to build with System One](https://docs.typesafe.ai/concepts/how-to-build-with-system-one), the [use-case map](https://docs.typesafe.ai/concept...

## Cookbooks

- [console cookbooks](projects/425-console-cookbooks.md) — README.md:425 — Official, copy-pasteable workflows. Full index: [console cookbooks](https://console.typesafe.ai/docs/cookbooks) and the [docs index](https://docs.typesafe.ai...
- [docs index](projects/425-docs-index.md) — README.md:425 — Official, copy-pasteable workflows. Full index: [console cookbooks](https://console.typesafe.ai/docs/cookbooks) and the [docs index](https://docs.typesafe.ai...
- [Parallel questions](projects/427-parallel-questions.md) — README.md:427 — Batch many questions over one state; one call instead of N.
- [Line-by-line search](projects/428-line-by-line-search.md) — README.md:428 — Score hundreds of line ids against a query with Choice + a Noul "does an answer exist?" check.
- [Re-ranking](projects/429-re-ranking.md) — README.md:429 — BM25 shortlist, then one TypeSafe question per query–candidate pair.
- [Guardrails for LLMs](projects/430-guardrails-for-llms.md) — README.md:430 — Screen messages in and out of an LLM; threshold probabilities in code.
- [Double-checking citations](projects/431-double-checking-citations.md) — README.md:431 — Whether a quote's context supports the claim; confidence gates human review.
- [Classifying RAG passages](projects/432-classifying-rag-passages.md) — README.md:432 — Keep, flag, or drop retrieved passages before the answering model.
- [Function calling](projects/433-function-calling.md) — README.md:433 — Map natural-language requests onto ordinary typed functions with closed-set arguments.
- [Skill suggestion](projects/434-skill-suggestion.md) — README.md:434 — Rank an agent skill catalog, then read only the top few.
- [Hierarchical classification](projects/435-hierarchical-classification.md) — README.md:435 — Beam search over deep taxonomies with Choice probabilities.
- [SDE cascade](projects/436-sde-cascade.md) — README.md:436 — Two-stage structured-data-extraction cascade (mini → verify → reasoning).
- [Date extraction](projects/437-date-extraction.md) — README.md:437 — Ask for named date parts, resolve and validate in code.
- [Pre-parsed value extraction](projects/438-pre-parsed-value-extraction.md) — README.md:438 — Regex candidates, then Jev selects the requested span.
- [Knowledge graph entity alignment](projects/439-knowledge-graph-entity-alignment.md) — README.md:439 — Score merge / leave unlinked / send to a curator.
- [Autoresearch feature discovery](projects/440-autoresearch-feature-discovery.md) — README.md:440 — Propose TypeSafe questions as numeric features for a supervised model.
- [Classification using confidence](projects/441-classification-using-confidence.md) — README.md:441 — Report a fine label only when confidence is high; otherwise climb the hierarchy.
- [Structure recovery](projects/442-structure-recovery.md) — README.md:442 — Reconstruct Markdown from de-formatted plain text.
- [Self-consistency: nouls](projects/443-self-consistency-nouls.md) — README.md:443 — Route uncertain probabilities to review without hiding the raw values.
- [Jev Cookbook](projects/444-jev-cookbook.md) — README.md:444 — Community cookbook: 15 runnable Node recipes that pass tickets, table rows, documents, invoices and emails as state, ask Choice, Noul and Score questions in ...

## Benchmarks and evaluations

- [Workflow evals](projects/450-workflow-evals.md) — README.md:450 — Official: four automation workflows, accuracy/cost/time per case, Jev vs frontier models.
- [typesafe-ai-benchmark](projects/451-typesafe-ai-benchmark.md) — README.md:451 — Jev vs Qwen 3.8 27B on Cerebras for the same System One questions.
- [Jev Rerank Bench](projects/452-jev-rerank-bench.md) — README.md:452 — Reranking comparison with raw provider responses, scoring code, and uncertainty intervals.
- [Jev Spam Eval](projects/453-jev-spam-eval.md) — README.md:453 — Zero-shot spam study vs trained TF-IDF baselines, with post-hoc-tuning caveats.
- [Jev Phishing Bench](projects/454-jev-phishing-bench.md) — README.md:454 — 2,000 emails: Jev vs Claude Haiku 4.5 on click-or-not, with calibration, latency, and cost. Haiku wins accuracy here.
- [jev-agent-failure-benchmark](projects/455-jev-agent-failure-benchmark.md) — README.md:455 — Who&When Pro (injected agent failures): Jev vs a strong LLM on who / which step / error category.
- [jev-sec-bench](projects/456-jev-sec-bench.md) — README.md:456 — Blind prompt-injection and vulnerable-code detection benches on public corpora.
- [Jev DSPy Lab](projects/457-jev-dspy-lab.md) — README.md:457 — DSPy companion that records and replays TypeSafe calls while measuring calibration, selective risk, abstention, latency, and cost.
- [jevcal](projects/458-jevcal.md) — README.md:458 — CLI that fits a per-question confidence threshold to a target accuracy on your own labeled data, and fails CI when a Jev update breaks locked thresholds.
- [ASSAY-001](projects/459-assay-001.md) — README.md:459 — Independent pre-registered check of Jev calibration and type safety on Banking77 / CLINC150. Split verdict, full logs. [Write-up](https://donttrustme.ai/assa...
- [Jev search rerank eval](projects/460-jev-search-rerank-eval.md) — README.md:460 — 9,831 labelled pairs: Jev rerank vs BM25 / bge-m3. Fusion wins; Jev alone does not beat embeddings.
- [Smoking-history extraction benchmark](projects/461-smoking-history-extraction-benchmark.md) — README.md:461 — 1,000 synthetic notes: Jev vs OpenAI structured outputs on accuracy, cost, and latency.
- [Jev Playground](projects/462-jev-playground.md) — README.md:462 — Benchmarks Jev against Luna, Haiku, and Gemini at choosing validated legal moves in explicit-state games.
- [jev-research-eval](projects/463-jev-research-eval.md) — README.md:463 — Reproducible eval harness plus field note for Jev Ultrafast research-browser tasks.

## Research and open models

- [jevlike](projects/469-jevlike.md) — README.md:469 — Train a small one-pass scorer mapping context + N text options to a probability per option. Doom / chess vision demos and a Wikispeedia example. Explicitly n...
- [openjev](projects/470-openjev.md) — README.md:470 — Can we run something Jev-like on a home RTX 3090? Reads option logits instead of generating text. Also [zhihz/openjev](https://github.com/zhihz/openjev) - an...
- [PocketJev](projects/471-pocketjev.md) — README.md:471 — On-device iPhone visual decisions with MLX + Qwen3-VL option logits. Camera + 3-choice, no text generation, ~1 s, no photo saved.
- [jev-visual](projects/472-jev-visual.md) — README.md:472 — Educational Jev-like visual inference on Apple Silicon: shared multimodal context, candidate scoring, sorting-factory / Breakout / gesture demos.
- [jevmlx](projects/473-jevmlx.md) — README.md:473 — Jev-style parallel constrained decisions for any MLX model on Apple Silicon: schema-valid JSON in one forward pass.
- [JEVfire](projects/474-jevfire.md) — README.md:474 — Jev-inspired parallel decisions for CUDA LLMs via vLLM, with a browser Mario demo (~71 ms/action locally).
- [decider](projects/475-decider.md) — README.md:475 — Qwen3.5-2B fine-tune that emits typed decisions with calibrated probabilities in one pass.
- [Parallel Constrained Decoding (Qwen2.5-1B-RLCD)](projects/476-parallel-constrained-decoding-qwen2-5-1b-r.md) — README.md:476 — Hugging Face space exploring open-source RLCD-style parallel constrained decoding.
- [eve-rlcd](projects/477-eve-rlcd.md) — README.md:477 — Jev-inspired 0.6B decision model trained with reinforcement learning from right/wrong feedback only (reward: outcome minus stated probability); answers paral...

## Articles and coverage

- [TypeSafe AI debuts model for machines that plays Doom](projects/481-typesafe-ai-debuts-model-for-machines-that.md) — README.md:481 — The Register's launch coverage.
- [Mini-Vibe Check: TypeSafe's Jev Judged Everything I've Written in 0.7 Seconds](projects/482-mini-vibe-check-typesafe-s-jev-judged-ever.md) — README.md:482 — Every's Mike Taylor runs Jev over his writing corpus: 1,709 judgments for under a cent.
- [Building a harness with Jev](projects/483-building-a-harness-with-jev.md) — README.md:483 — LangChain on model routing and gating dangerous tool calls behind a typed decision.
- [Jev, from a developer's angle](projects/484-jev-from-a-developer-s-angle.md) — README.md:484 — Flavio Copes on triage, RAG filtering, citation checks, and confidence gates.
- [Jev, Sorted](projects/485-jev-sorted.md) — README.md:485 — What the launch claims survive a reading of the primary sources, and what is still vendor-reported.
- [TypeSafe Jev played chess (and landed next to reasoning models)](projects/486-typesafe-jev-played-chess-and-landed-next-.md) — README.md:486 — Maxim Saplin constrains chess to legal-move Choices.
- [Jev: one judge call, or twelve dimension scores?](projects/487-jev-one-judge-call-or-twelve-dimension-sco.md) — README.md:487 — Independent measurement on three classification tasks, with token costs and false-positive rates.
- [Testing Jev on public and private data: classifier or filter?](projects/488-testing-jev-on-public-and-private-data-cla.md) — README.md:488 — 16,000 calls vs gpt-5.4-mini and gpt-5.6-luna; where it wins, where it breaks, and a threshold procedure.
- [Jev vs Mistral and Gemini for event validation](projects/489-jev-vs-mistral-and-gemini-for-event-valida.md) — README.md:489 — Head-to-head at validating local event listings.
- [TypeSafeのJevを正しく驚く、それってLLMでできませんか？](projects/490-typesafe-jev-llm.md) — README.md:490 — (Japanese) Reproduces the JSON-vs-logit shortcut on Gemma and compares Jev with LLMs on the public Mario harness.
- [jev 同士に五目並べで対戦させた](projects/491-jev.md) — README.md:491 — (Japanese) Jev vs Jev gomoku with source and timing logs.
- [Jev on AI Wiki](projects/492-jev-on-ai-wiki.md) — README.md:492 — Community-maintained reference page.

## Discussions

- [Introducing System One Models and Jev](projects/496-introducing-system-one-models-and-jev.md) — README.md:496 — The 1,800-point Hacker News launch thread; the sceptical reading of the benchmarks lives here.
- [Launch thread by Diogo Almeida](projects/497-launch-thread-by-diogo-almeida.md) — README.md:497 — TypeSafe's founder argues RLCD-trained decision models are a shorter path to economic value than chat models.
- [TypeSafe AI releases Jev (r/singularity)](projects/498-typesafe-ai-releases-jev-r-singularity.md) — README.md:498 — Reddit frames Jev as a low-hallucination, low-cost decision model for software rather than chat.
- [Testing Jev for Pi extensions (r/PiCodingAgent)](projects/499-testing-jev-for-pi-extensions-r-picodingag.md) — README.md:499 — Builders using Jev as an agent tool-use safety layer.
- [Jev "playing" Minecraft (r/accelerate)](projects/500-jev-playing-minecraft-r-accelerate.md) — README.md:500 — Work-in-progress demo, including fleeing zombies at night.
- [Model router built with Jev](projects/501-model-router-built-with-jev.md) — README.md:501 — Jev decides which model should serve a request before it is forwarded.
- [MLP on Qwen 4B mimicking Jev](projects/502-mlp-on-qwen-4b-mimicking-jev.md) — README.md:502 — A small MLP on top of Qwen 4B reproduces Jev-like decision behaviour.
- [Running a local TypeSafe Jev](projects/503-running-a-local-typesafe-jev.md) — README.md:503 — (Japanese) Local Jev-style decision model attempt.
- [Jev as an AI agent safety monitor](projects/504-jev-as-an-ai-agent-safety-monitor.md) — README.md:504 — Checking each agent action first reportedly catches most attacks with almost no false blocks.
- [Rethinking security engineering with Jev](projects/505-rethinking-security-engineering-with-jev.md) — README.md:505 — Argues purely engineering decisions in security work belong to Jev rather than a chat model.
- [Ask Jev anything, it will judge](projects/506-ask-jev-anything-it-will-judge.md) — README.md:506 — Public Convex-backed demo inviting one million judged questions.
- [First Jev use case in a Mac app](projects/507-first-jev-use-case-in-a-mac-app.md) — README.md:507 — A shipped Mac app routes setup and troubleshooting questions to Jev when no language model is loaded.
- [Jev 中文解读](projects/508-jev.md) — README.md:508 — (Chinese) The System One category explained as a calibrated, typed decision layer for code.
- [Launch roundup](projects/509-launch-roundup.md) — README.md:509 — Browser, papers, email, trading, and games in one thread.

## FAQ

- [FAQ: What is Jev?](projects/515-faq-what-is-jev.md) — README.md:515 — Jev is an AI model from TypeSafe AI, launched in early access on September 15, 2026. It is the first "System One" model: instead of generating text, it evalu...
- [FAQ: What is TypeSafe AI?](projects/519-faq-what-is-typesafe-ai.md) — README.md:519 — TypeSafe AI is a San Francisco AI lab founded by Diogo Almeida, previously at OpenAI, where he worked on instruction-following methods. The company raised $4...
- [FAQ: Is Jev an LLM?](projects/523-faq-is-jev-an-llm.md) — README.md:523 — No. It reads natural language but never generates text. The answer space is defined in advance by your questions, so outputs are type-safe by construction an...
- [FAQ: What is RLCD?](projects/527-faq-what-is-rlcd.md) — README.md:527 — Reinforcement Learning for Calibrated Decisions — TypeSafe's training method for System One models. Where RLHF optimizes for responses humans prefer, RLCD op...
- [FAQ: How much does Jev cost?](projects/531-faq-how-much-does-jev-cost.md) — README.md:531 — $0.042 per million input tokens; output tokens are free. A typical typed question costs a tiny fraction of a cent, which is why the featured builds above rep...
- [FAQ: How do I get access?](projects/535-faq-how-do-i-get-access.md) — README.md:535 — Three ways: join the early-access waitlist at [typesafe.ai](https://typesafe.ai), use [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev) (model id...
- [FAQ: What are Jev's limits?](projects/539-faq-what-are-jev-s-limits.md) — README.md:539 — Choice questions cap at 255 options. Text only — no images, audio, or video. Listed rate limits are 250,000 tokens/second and 1,200 requests/minute, and Type...
- [FAQ: What is a System One model?](projects/543-faq-what-is-a-system-one-model.md) — README.md:543 — TypeSafe's name for a model class built for fast, structured decisions inside software — as opposed to chat models that generate text for humans. Named after...

## Related lists

- [awesome-jev (AnotiaWang)](projects/547-awesome-jev-anotiawang.md) — README.md:547 — Community list of Jev applications, libraries, and resources. English and 简体中文.
- [awesome-jev (yibie)](projects/548-awesome-jev-yibie.md) — README.md:548 — Jev projects and discussions organized by application domain.
- [awesome-jev (cobanov)](projects/549-awesome-jev-cobanov.md) — README.md:549 — Curated, source-backed list of Jev projects, sorted by decision domain.
- [awesome-jev-by-typesafe (Anil-matcha)](projects/550-awesome-jev-by-typesafe-anil-matcha.md) — README.md:550 — Evidence-backed use cases, patterns, and starter code.
- [awesome-jev-typesafe (valentynkit)](projects/551-awesome-jev-typesafe-valentynkit.md) — README.md:551 — CC0, awesome-lint clean, sorted by what you would install, with a short know-before-you-build section on the limits.
- [typesafe-ai on PyPI](projects/552-typesafe-ai-on-pypi.md) — README.md:552 — Community redirect shim; the real package is `typesafe-sdk`. Registered to block slopsquatting.

## License

- [CONTRIBUTING.md](projects/556-contributing-md.md) — README.md:556 — See [CONTRIBUTING.md](CONTRIBUTING.md). In short: open a pull request that adds a project with a link and a one-line description. It should be useful, intere...
- [CC0 1.0](projects/562-cc0-1-0.md) — README.md:562 — [CC0 1.0](LICENSE) — this list is dedicated to the public domain.
