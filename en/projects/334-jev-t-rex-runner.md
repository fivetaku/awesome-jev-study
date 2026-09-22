# jev-t-rex-runner

[한국어](../../ko/projects/334-jev-t-rex-runner.md) · [English](../../en/projects/334-jev-t-rex-runner.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L334) `README.md:334` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Demos and games
- URL: https://github.com/joshlarsen/jev-t-rex-runner
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [jev-t-rex-runner](https://github.com/joshlarsen/jev-t-rex-runner) - The Chrome dinosaur game, played by Jev.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `joshlarsen/jev-t-rex-runner`, 0 stars, SPDX BSD-3-Clause, push 2026-09-17, archived False, language JavaScript.
- The list's CC0 does not cover this repository. Its license is BSD-3-Clause.
- API description: Chrome dino game played by Typesafe AI Jev model

## Role Jev plays

Jev's place is the next legal move, chosen from a state the game code rendered as text or as options. The list says: The Chrome dinosaur game, played by Jev. The game, the legal-move generator, and the input injection sit outside the model. This page did not trace them and did not remeasure author-reported rates or costs.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM can name a move in prose. Turn-based games can afford the wait if you can parse the move. Real-time loops cannot, if the vendor-reported frontier range of 3–329 seconds is even roughly the right order of magnitude. That range was not measured on this game. Illegal moves are a parse problem for the LLM and a construction problem for Choice: the list's chess row says illegal moves are impossible because the options are the legal moves.

## If this were a script

Inference. Where a simulator exists, minimax or a heuristic plays the tactical game without a model. It is useless in a game you cannot score with code, and it is usually stronger than a text judge at games where the evaluation is exact.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
