# ProgressGate

[한국어](../../ko/projects/283-progressgate.md) · [English](../../en/projects/283-progressgate.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L283) `README.md:283` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Developer tools and code review
- URL: https://github.com/AshutoshVJTI/progressgate
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [ProgressGate](https://github.com/AshutoshVJTI/progressgate) - Detects semantic stagnation in agent loops: Jev judges the trajectory; code returns CONTINUE / WARN / REPLAN / HALT.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `AshutoshVJTI/progressgate`, 0 stars, SPDX MIT, push 2026-09-18, archived False, language TypeScript.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Detect semantic stagnation in AI agent loops

## Role Jev plays

The list says: Detects semantic stagnation in agent loops: Jev judges the trajectory; code returns CONTINUE / WARN / REPLAN / HALT. Rows filed in this section are usually a judgment over a diff, a log, a commit, or a string already extracted, and ordinary code keeps the filesystem and the git calls. That is the section's shape. It is not a finding that this row matches it. This page did not trace the code.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM review writes a comment. That is the better product when you wanted prose. It is a worse product when you wanted a label you can threshold, store, and compare across runs. Output tokens and unbounded wording are the cost.

## If this were a script

Inference. Linters and regexes are precise on patterns they were given, including secrets that match a known shape. They do not judge whether a change does what the pull request claimed.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
