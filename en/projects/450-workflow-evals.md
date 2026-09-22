# Workflow evals

[한국어](../../ko/projects/450-workflow-evals.md) · [English](../../en/projects/450-workflow-evals.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L450) `README.md:450` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Benchmarks and evaluations
- URL: https://evals.typesafe.ai
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [Workflow evals](https://evals.typesafe.ai) - Official: four automation workflows, accuracy/cost/time per case, Jev vs frontier models.

## What was checked

- This evals fetch does not contain 67.8, 0.0004, 74.1, or 73.1. The body says reference labels for that eval are an average of GPT-6 Astra and Claude Fable 5.1. Means outside that sentence are not confirmed here.

## Role Jev plays

This row is a harness or a published eval, not a product feature. The list says: Official: four automation workflows, accuracy/cost/time per case, Jev vs frontier models. Official numbers on the list are vendor-reported. This study did not rerun the harness. A fetch of evals.typesafe.ai on 2026-09-22 did not contain the headline percentages an earlier, longer extract had quoted, so those percentages are not restated here.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. In these rows the LLM is often the comparison point, not a drop-in replacement for the harness. Replacing Jev with an LLM changes the unit of cost from an input-priced decision to a generated answer, and it changes latency by the vendor-reported gap. It does not by itself reproduce a benchmark.

## If this were a script

Inference. A script baseline, exact match or a lexical rank, is meaningful only if the harness includes one. This page does not claim it does unless the list sentence says so.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
