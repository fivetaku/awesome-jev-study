# zio-typesafe-ai

[한국어](../../ko/projects/231-zio-typesafe-ai.md) · [English](../../en/projects/231-zio-typesafe-ai.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L231) `README.md:231` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: SDKs and clients
- URL: https://github.com/jamesward/zio-typesafe-ai
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - Scala / ZIO: [zio-typesafe-ai](https://github.com/jamesward/zio-typesafe-ai) - ZIO client with a small DSL for noul / choice / score.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `jamesward/zio-typesafe-ai`, 3 stars, SPDX Apache-2.0, push 2026-09-18, archived False, language Scala.
- The list's CC0 does not cover this repository. Its license is Apache-2.0.

## Role Jev plays

This repository is a client, not the model. Jev stays at the remote System One endpoint. The package is the call in one language. The list's sentence: ZIO client with a small DSL for noul / choice / score.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The list says community clients are not affiliated with TypeSafe (README.md:213).

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The language binding is incidental. An LLM path replaces system_one with a chat completion and adds a parser for the text. You take on output tokens and the chance the text leaves the option list. The official quickstart shape is in the list at README.md:102-159. This page did not re-run it.

## If this were a script

Inference. If the decision is a rule you can write down, you do not need this client or Jev. The SDK earns its place only where the question is semantic and the answer has to stay inside options your code listed.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
