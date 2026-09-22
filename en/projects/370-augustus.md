# augustus

[한국어](../../ko/projects/370-augustus.md) · [English](../../en/projects/370-augustus.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L370) `README.md:370` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Agent tools and MCP servers
- URL: https://github.com/24601/Augustus
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [augustus](https://github.com/24601/Augustus) - Design-judgment skill: maps Choice/Score/Noul onto classical methods with a composition algebra, question-design diagnosis, and falsifying validation gates.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `24601/Augustus`, 6 stars, SPDX MIT, push 2026-09-22, archived False, language Python.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: Agent skill for the decision-model class (classifiers, encoders/decoders, specialized AR heads, System One). TypeSafe Jev is the dominant exemplar. Composition algebra, question de

## Role Jev plays

Jev is exposed as a tool an agent can call, or as a gate in front of an agent that already writes text. The list says: Design-judgment skill: maps Choice/Score/Noul onto classical methods with a composition algebra, question-design diagnosis, and falsifying validation gates. The agent loop, the permissions, and the side effects are not Jev. This page did not trace them.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The agent is already an LLM path. Jev replaces only the moments where the agent should not improvise: a verdict, a route, a stop/go. Leaving those moments to the same chat model means the verdict is more prose, with no closed option list.

## If this were a script

Inference. A hook written as a script can block on a regex or a missing test. It cannot apply a plain-language completion rule it was not coded for. The list's stop-hook rows claim that distinction. The source was not opened.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
