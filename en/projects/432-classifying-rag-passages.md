# Classifying RAG passages

[한국어](../../ko/projects/432-classifying-rag-passages.md) · [English](../../en/projects/432-classifying-rag-passages.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L432) `README.md:432` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Cookbooks
- URL: https://docs.typesafe.ai/cookbooks/classifying_rag_passages
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [Classifying RAG passages](https://docs.typesafe.ai/cookbooks/classifying_rag_passages) - Keep, flag, or drop retrieved passages before the answering model.

## What was checked

- Nothing beyond the list sentence was confirmed for this row.

## Role Jev plays

This row is a recipe. The list says: Keep, flag, or drop retrieved passages before the answering model. The setup, as far as the list goes, is a state plus Choice, Noul, or Score questions, with thresholds left in code. The recipe was not run. Community cookbook code was not copied.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

This is a document row. The setup is the question shape the list wrote down. The sample was not run.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The LLM version of a cookbook step generates the classification as text, or answers the user directly. You lose the closed option list and you pay output tokens on every row of a batch. Some recipes, such as a citation check, want a judgment rather than a rewritten passage. Those are the ones that stop fitting.

## If this were a script

Inference. A script can do the non-semantic half the list already assigns to code: resolve a date, validate a span, apply a threshold. The semantic half, such as whether a quote supports a claim, is the part a regex only approximates.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
