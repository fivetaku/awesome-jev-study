# Jev Search

[한국어](../../ko/projects/259-jev-search.md) · [English](../../en/projects/259-jev-search.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L259) `README.md:259` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Search, retrieval, and data
- URL: https://github.com/superagents-lab/jev-search
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [Jev Search](https://github.com/superagents-lab/jev-search) - Web search app using Choice and Noul judgments to select sources, time ranges, and query candidates, then rank results retrieved through Search1API. Live demo: [jev.s1.dev](https://jev.s1.dev).

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `superagents-lab/jev-search`, 399 stars, SPDX MIT, push 2026-09-20, archived False, language TypeScript.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Search the web with TypeSafe's Jev: source selection, query understanding and relevance ranking. Built with Search1API.

## Role Jev plays

Jev scores, filters, or picks among passages, rows, or queries the rest of the system already fetched. The list says: Web search app using Choice and Noul judgments to select sources, time ranges, and query candidates, then rank results retrieved through Search1API. Live demo: [jev.s1.dev](https://jev.s1.dev). Retrieval itself stays a database, index, or crawler. This page did not trace that pipeline.

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
