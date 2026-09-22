# Vercel AI Gateway

[한국어](../../ko/projects/100-vercel-ai-gateway.md) · [English](../../en/projects/100-vercel-ai-gateway.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L100) `README.md:100` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Pricing, limits, and access
- URL: https://vercel.com/ai-gateway/models/jev
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> | No-waitlist access | [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev) (`typesafe-ai/jev`) and [Cloudflare Workers AI](https://developers.cloudflare.com/ai/models/typesafe/jev/) (`typesafe/jev`) |

## What was checked

- This Vercel fetch contains the model id `typesafe-ai/jev`, and the price chrome shows 32K and Free. The body contains neither `0.042` nor `waitlist`. Do not say this page confirms the list's price or the no-waitlist claim.

## Role Jev plays

This row is TypeSafe's own page or the list's own table, not a community integration. What it is for: [Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev) (`typesafe-ai/jev`) and [Cloudflare Workers AI](https://developers.cloudflare.com/ai/models/typesafe/jev/) (`typesafe/jev`)

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence names: `typesafe-ai/jev`, `typesafe/jev`. That is the list's sentence, not a config file traced in source.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The comparison the list draws is structural. An LLM writes text and you parse it. Jev returns a value inside a space you defined. Swapping the model does not preserve the type of the result. The latency and price ranges in the launch post are the vendor's, not a rerun of this page.

## If this were a script

Inference. A script can implement the control flow around a decision, and it can implement a decision only when the rule is already code. It cannot stand in for a page that exists to explain a model.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
