# 가격·한도 표

[한국어](../../ko/projects/091-item.md) · [English](../../en/projects/091-item.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L91) `README.md:91` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Pricing, limits, and access
- URL: https://docs.typesafe.ai/models
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

This row is not a one-line bullet. What follows restates that table or block.

> The list's price table (README.md:91-100), a snapshot it dates September 18, 2026. `jev-latest` is `jev-1.13.0`. Endpoint `POST https://api.typesafe.ai/v1/systemone`. $0.042 / 1M input tokens, output free. 250,000 tokens/second and 1,200 requests/minute. Choice up to 255 options. Text only. Direct access is a waitlist. The list's no-waitlist path is Vercel (`typesafe-ai/jev`) and Cloudflare (`typesafe/jev`).

## What was checked

- Models page, this fetch: 64k tokens per request, and 32k for state plus the longest question. `jev-latest` and `jev-preview` both point at `jev-1.13.0`. Output tokens are free. The page says there is no preview build right now. The list's price table (README.md:91-100) does not include the 64k or 32k limits. The Choice cap of 255 is on the Choice doc and at README.md:97, not as a models-page sentence.

## Role Jev plays

This row is TypeSafe's own page or the list's own table, not a community integration. What it is for: The list's price table (README.md:91-100), a snapshot it dates September 18, 2026. `jev-latest` is `jev-1.13.0`. Endpoint `POST https://api.typesafe.ai/v1/systemone`. $0.042 / 1M input tokens, output free. 250,000 tokens/second and 1,200 requests/minute. Choice up to 255 options. Text only. Direct access is a waitlist. The list's no-waitlist path is Vercel (`typesafe-ai/jev`) and Cloudflare (`typesafe/jev`).

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

This is a document row. The setup is the question shape the list wrote down. The sample was not run.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The comparison the list draws is structural. An LLM writes text and you parse it. Jev returns a value inside a space you defined. Swapping the model does not preserve the type of the result. The latency and price ranges in the launch post are the vendor's, not a rerun of this page.

## If this were a script

Inference. A script can implement the control flow around a decision, and it can implement a decision only when the rule is already code. It cannot stand in for a page that exists to explain a model.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
