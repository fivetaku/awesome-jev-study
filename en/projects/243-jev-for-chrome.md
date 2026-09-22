# Jev for Chrome

[한국어](../../ko/projects/243-jev-for-chrome.md) · [English](../../en/projects/243-jev-for-chrome.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L243) `README.md:243` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Browser and computer-use agents
- URL: https://github.com/chy4pro/jev-for-chrome
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [Jev for Chrome](https://github.com/chy4pro/jev-for-chrome) - Unofficial Chrome extension (Manifest V3) port of Jev Ultrafast: Jev picks the operation and DOM element in one request, a small text model writes typed values, and it runs in the user's own tabs through OpenRouter, TypeSafe or Cloudflare; includes a 17-task headless-Chromium suite with recorded traces.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `chy4pro/jev-for-chrome`, 18 stars, SPDX MIT, push 2026-09-22, archived False, language TypeScript.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Jev for Chrome: drives the tab you are looking at with TypeSafe Jev, a sub-second decision model. Community port of browser-use/jev-ultrafast, not affiliated with TypeSafe.

## Role Jev plays

Jev's place, if the list is right, is the decision inside a browser or computer-use loop. The list says: Unofficial Chrome extension (Manifest V3) port of Jev Ultrafast: Jev picks the operation and DOM element in one request, a small text model writes typed values, and it runs in the user's own tabs through OpenRouter, TypeSafe or Cloudflare; includes a 17-task headless-Chromium suite with recorded traces. Observing the page and performing the click are ordinary code. This page did not trace that loop, and it does not claim this project sees pixels. The Doom write-up is the one that says text state rather than frames, and that sentence is not copied onto other agents.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM would write the next action as text and the program would parse it. The launch post's vendor-reported end-to-end range is 70–500 ms for Jev and 3–329 seconds for frontier models. That is not a measurement of this project. A loop that has to act while a page is waiting is where that gap changes the design. Output tokens stay on the LLM bill.

## If this were a script

Inference. A script is selectors and a fixed order of clicks. It is cheaper and deterministic while the DOM stays still. It does not decide which of several similar controls is the one this task wants once the markup changes.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
