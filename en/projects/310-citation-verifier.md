# citation-verifier

[한국어](../../ko/projects/310-citation-verifier.md) · [English](../../en/projects/310-citation-verifier.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L310) `README.md:310` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Business and vertical apps
- URL: https://github.com/MarissaFamularo/citation-verifier
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [citation-verifier](https://github.com/MarissaFamularo/citation-verifier) - Checks whether each cited paper actually supports the sentence citing it: Claude locates the quote, Jev scores the support, a human makes the final call.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `MarissaFamularo/citation-verifier`, 5 stars, SPDX MIT, push 2026-09-17, archived False, language JavaScript.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Check whether each cited paper supports the sentence citing it. Claude proves the quote, TypeSafe's Jev scores it, a human decides.

## Role Jev plays

The list says: Checks whether each cited paper actually supports the sentence citing it: Claude locates the quote, Jev scores the support, a human makes the final call. Rows in this section are usually a closed label, hire or not, which intent, buy or sell, allow or block, with money, messages, and records left in ordinary code. Those examples are the section's, not a finding that this row is one of them. This page did not trace the side effects.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM writes a rationale. That is harder to batch and harder to threshold. It is what you want when a person must read the reason. It is not what you want for a thousand identical judgments.

## If this were a script

Inference. Rules on structured fields work when the signal is already a column. They fail on free text that does not repeat the keyword.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
