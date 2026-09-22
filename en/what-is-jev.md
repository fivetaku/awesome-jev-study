# What Jev is

[한국어](../ko/what-is-jev.md) · [English](../en/what-is-jev.md)

This page is pinned to the awesome-jev list at `22570dcd` and to pages fetched on 2026-09-22. Vendor numbers stay vendor numbers. Nothing here was remeasured by calling the API.

## The model

Jev is TypeSafe's first public System One model. The list's own banner says it returns typed decisions, Choice, Score, and Noul, with probabilities, instead of generated text. The models page fetched that day calls it TypeSafe's flagship model and says every model on the page is served by `POST /v1/systemone`.

It reads natural language. The list's FAQ says it never generates text, so a value outside the options you passed is not a possible output (README.md:521-523). The list also says it is not a replacement for an LLM. When you need free-form text, Jev routes, retrieves, verifies, or guards, and the LLM writes inside boundaries your code enforces (README.md:85).

## The three questions

The list (README.md:60-66) says questions in one request run in parallel against the same state.

| Question | What it decides | What comes back |
|---|---|---|
| Choice | One option from the list you passed | `choice`, `probabilities`, `confidence` |
| Score | Where the state sits on a rubric | `score`, `probabilities`, `confidence` |
| Noul | Whether a statement holds | `noul`, from 0 to 1 |

Choice accepts up to 255 options. That sentence is on the Choice doc and in the list's price table (README.md:97). It is not a sentence on the models page. Adding options costs a few tokens each, which is the Choice doc's wording.

Your code owns composition, thresholds, and side effects. The list says that directly (README.md:68).

## Price, limits, access

The list's table is a snapshot it dates September 18, 2026 (README.md:89-100).

- Alias `jev-latest`, version it names: `jev-1.13.0`
- `POST https://api.typesafe.ai/v1/systemone`
- $0.042 per 1M input tokens, output tokens free
- 250,000 tokens/second, 1,200 requests/minute, and the list says limits can change
- Choice up to 255 options
- Text only. No images, audio, or video
- Direct access: early-access waitlist
- No-waitlist path, as the list states it: Vercel AI Gateway id `typesafe-ai/jev`, Cloudflare Workers AI id `typesafe/jev`

Checked the same week:

- Models page, doc. Price line "$42 / $0.042" per billion / per million tokens. Output tokens free, charged on input. Context 64k tokens per request, and 32k for state plus the longest question. Both `jev-latest` and `jev-preview` point at `jev-1.13.0`. The page says there is no preview build right now, and aliases can move. The list's table does not mention 64k or 32k.
- Launch post, doc, byline Diogo Almeida, founder. LLM input "from $0.20 to $10 / MTok". Jev "$0.042 / MTok ($42 per billion tokens)". Output "FREE". End to end "70ms-500ms" for TypeSafe and "3 to 329 seconds" for frontier models. RLCD is Reinforcement Learning for Calibrated Decisions: the list says it optimizes for honest probabilities, where RLHF optimizes for answers people prefer. These ranges are the vendor's comparison. `$40M`, `40 million`, and `$40 ` are not in that post. `40x` is a speed factor. The FAQ's "$40M raised" (README.md:519) is unverified.
- Vercel, this fetch, run. The id `typesafe-ai/jev` is there. The chrome shows 32K and Free. The strings `0.042` and `waitlist` are not. Do not treat the list's price or "no waitlist" as confirmed by this page.
- Cloudflare, doc. Id `typesafe/jev`, context window 32,000 tokens, `env.AI.run`. The price amount is not on the page. Example titles include structured refund review, support department routing, and account risk assessment.

The list says early access started September 15, 2026 (README.md:20). That date is the list's statement.

## What a call looks like

The list's quick start (README.md:102-159) was not executed. It says:

- Create a key in the TypeSafe console. The client reads `TYPESAFE_API_KEY`.
- Python: `pip install typesafe-sdk`. `TypeSafeClient.system_one` with `Choice`, `Noul`, and `Score` on one state.
- JavaScript: `npm install @typesafe-ai/sdk`. `client.systemOne` with `choice`, `noul`, and `score`.
- On Vercel AI Gateway: `experimental_evaluate` and the model id `typesafe-ai/jev`.

The quickstart page we fetched shows the same POST and Bearer auth. The Python class names above are the list's example.

The agent-skill page matches the list's install lines (README.md:353): `claude plugin marketplace add typesafe-ai/skills`, then `claude plugin install typesafe@typesafe-ai`, or `npx skills add typesafe-ai/skills --skill typesafe-ai`.

## What this list is

The list is unofficial and not affiliated with TypeSafe (README.md:20, footer at README.md:566). It is maintained by @kraayenjon as part of madewithjev.com. CC0 covers the list text. It does not cover linked repositories. One of those, usenotra/notra, is AGPL-3.0. This study does not copy that code.

Featured cost and latency figures are author-reported. The list says so (README.md:209). They were not remeasured.
