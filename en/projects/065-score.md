# Score

[한국어](../../ko/projects/065-score.md) · [English](../../en/projects/065-score.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L65) `README.md:65` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: What is Jev?
- URL: https://docs.typesafe.ai/primitives/score
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> | [Score](https://docs.typesafe.ai/primitives/score) | Rate the state on a rubric | `score`, `probabilities`, `confidence` |

## What was checked

- Numbers printed in the list: `score`, `probabilities`, `confidence`. Author-reported (README.md:209). Not remeasured.

## Role Jev plays

This row is one question type, not a third-party app. Jev's role is the question itself: Rate the state on a rubric Choice picks one option you listed. Score places the state on a rubric. Noul answers whether a statement holds, as a number from 0 to 1. The list says questions in one request run in parallel against the same state (README.md:60).

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

This is a document row. The setup is the question shape the list wrote down. The sample was not run.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM would answer in prose. You would then parse a label, and the label can be a word you did not offer. You pay for output tokens. Jev's answer is one of the values in the question, plus probabilities. The launch post's vendor-reported range is 70–500 ms end to end for Jev and 3–329 seconds for frontier models, and LLM input from $0.20 to $10 / MTok against Jev's $0.042 with output free. Those figures are not a measurement of this row.

## If this were a script

Inference. A script can return a label only when the rule is already explicit: a keyword, a regex, a threshold on a field. It will not read a new phrasing of the same intent. Where the rule is truly closed, the script is the better instrument and Jev is unnecessary.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
