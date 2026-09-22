# jev-ultrafast

[한국어](../../ko/projects/194-jev-ultrafast.md) · [English](../../en/projects/194-jev-ultrafast.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L194) `README.md:194` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Featured builds with real numbers
- URL: https://madewithjev.com/builds/jev-ultrafast
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> | [jev-ultrafast](https://madewithjev.com/builds/jev-ultrafast) | Browser Use's agent with the next-action decision moved to Jev | ~2.9k stars | [GitHub](https://github.com/browser-use/jev-ultrafast) |

## What was checked

- Numbers printed in the list: ~2.9k stars. Author-reported (README.md:209). Not remeasured.
- The star figure splits three ways. The list cell says ~2.9k (README.md:194). The madewithjev page title on 2026-09-22 said 17.3k. The GitHub API that day returned 17568 for browser-use/jev-ultrafast. The page says counts come from the API and move daily. None of these remeasures the list's ~2.9k.

## Role Jev plays

Jev's place, if the list is right, is the decision inside a browser or computer-use loop. The list says: Browser Use's agent with the next-action decision moved to Jev Observing the page and performing the click are ordinary code. This page did not trace that loop, and it does not claim this project sees pixels. The Doom write-up is the one that says text state rather than frames, and that sentence is not copied onto other agents.

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
