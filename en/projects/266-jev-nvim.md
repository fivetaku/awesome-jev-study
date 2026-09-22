# jev.nvim

[한국어](../../ko/projects/266-jev-nvim.md) · [English](../../en/projects/266-jev-nvim.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L266) `README.md:266` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Search, retrieval, and data
- URL: https://github.com/valentynkit/jev.nvim
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [jev.nvim](https://github.com/valentynkit/jev.nvim) - Neovim plugin that splits the current buffer into functions with Treesitter, asks Jev a plain-language question against each one, and lists the answers in the quickfix window ranked by probability.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `valentynkit/jev.nvim`, 5 stars, SPDX MIT, push 2026-09-19, archived False, language Lua.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Neovim: ask the buffer a question, get a quickfix list. Treesitter splits functions, Jev scores each one, probabilities land as virtual text

## Role Jev plays

Jev scores, filters, or picks among passages, rows, or queries the rest of the system already fetched. The list says: Neovim plugin that splits the current buffer into functions with Treesitter, asks Jev a plain-language question against each one, and lists the answers in the quickfix window ranked by probability. Retrieval itself stays a database, index, or crawler. This page did not trace that pipeline.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM would summarize or rewrite the hits. If you only needed a rank or a keep/drop, you paid to generate text you discard. A judge that returns a score leaves the prose, if you still need it, to a later call.

## If this were a script

Inference. Keyword rank and filters work when the query words are in the document. They miss a paraphrase. They are the right tool when the match really is lexical.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
