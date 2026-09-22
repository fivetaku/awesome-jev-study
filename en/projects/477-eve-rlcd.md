# eve-rlcd

[한국어](../../ko/projects/477-eve-rlcd.md) · [English](../../en/projects/477-eve-rlcd.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L477) `README.md:477` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Research and open models
- URL: https://github.com/anthony-maio/eve-rlcd
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [eve-rlcd](https://github.com/anthony-maio/eve-rlcd) - Jev-inspired 0.6B decision model trained with reinforcement learning from right/wrong feedback only (reward: outcome minus stated probability); answers parallel Choice, Score and Noul questions over one state without generating text, with an RLVR ablation and [open weights](https://huggingface.co/anthonym21/qwen3-0.6b-rlcd-decision). Explicitly not a reproduction of TypeSafe's method.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `anthony-maio/eve-rlcd`, 6 stars, SPDX MIT, push 2026-09-21, archived False, language Python.
- The list's CC0 does not cover this repository. Its license is MIT.
- API description: code
- The API description and README front read on 2026-09-22 did not contain Jev, TypeSafe, or System One. Only the list sentence states the link.

## Role Jev plays

This row is a paper, a local model, or an open artifact sitting next to the claim. The list says: Jev-inspired 0.6B decision model trained with reinforcement learning from right/wrong feedback only (reward: outcome minus stated probability); answers parallel Choice, Score and Noul questions over one state without generating text, with an RLVR ablation and [open weights](https://huggingface.co/anthonym21/qwen3-0.6b-rlcd-decision). Explicitly not a reproduction of TypeSafe's method. Jev is not assumed to be a dependency. The front matter was checked for whether it even names Jev. Source was not traced.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. If the artifact is itself a language model, the difference is the task. Jev does not generate the answer text. A local LLM does, unless someone has trained it to mimic closed decisions. One list row claims a small MLP on Qwen does that. That claim was not tested here.

## If this were a script

Inference. A script can reproduce an evaluation's scoring rules. It cannot reproduce a learned decision. Treating a research row as a library to vendor is a category error.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
