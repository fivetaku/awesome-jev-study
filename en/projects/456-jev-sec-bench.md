# jev-sec-bench

[한국어](../../ko/projects/456-jev-sec-bench.md) · [English](../../en/projects/456-jev-sec-bench.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L456) `README.md:456` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Benchmarks and evaluations
- URL: https://github.com/Gaurav-Gosain/jev-sec-bench
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [jev-sec-bench](https://github.com/Gaurav-Gosain/jev-sec-bench) - Blind prompt-injection and vulnerable-code detection benches on public corpora.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `Gaurav-Gosain/jev-sec-bench`, 2 stars, SPDX MIT, push 2026-09-16, archived False, language Go.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Blind security benchmarks for Jev, TypeSafe's System One model: prompt injection and vulnerable code detection, built on jev-go

## Role Jev plays

This row is a harness or a published eval, not a product feature. The list says: Blind prompt-injection and vulnerable-code detection benches on public corpora. Official numbers on the list are vendor-reported. This study did not rerun the harness. A fetch of evals.typesafe.ai on 2026-09-22 did not contain the headline percentages an earlier, longer extract had quoted, so those percentages are not restated here.

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
