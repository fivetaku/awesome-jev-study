# jev-router

[한국어](../../ko/projects/293-jev-router.md) · [English](../../en/projects/293-jev-router.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L293) `README.md:293` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Model routing
- URL: https://github.com/gargpratyush/jev-router
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [jev-router](https://github.com/gargpratyush/jev-router) - Per-turn routing for Claude Code and Codex: simple work to the fast tier, hard work to the strong tier. `npm i -g jev-router`.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `gargpratyush/jev-router`, 328 stars, SPDX MIT, push 2026-09-19, archived False, language JavaScript.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Route to the cheapest model in claude code for your task using jev-router

## Role Jev plays

Jev's Choice picks the next model, skill, or route. Generation, if any, happens after that pick. The list says: Per-turn routing for Claude Code and Codex: simple work to the fast tier, hard work to the strong tier. `npm i -g jev-router`. This page did not trace the routing rule in source.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence names: `npm i -g jev-router`. That is the list's sentence, not a config file traced in source.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. You can ask a chat model to pick a route. You pay a full generation for a decision, and the answer can drift off the route list. A Choice cannot name a route you did not pass in.

## If this were a script

Inference. Keyword, length, and file-type rules are cheap and brittle. They are enough when the route really does follow those signals, and they fail when 'hard' is a property of the prose.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
