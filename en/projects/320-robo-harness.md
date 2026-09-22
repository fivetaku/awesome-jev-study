# robo-harness

[한국어](../../ko/projects/320-robo-harness.md) · [English](../../en/projects/320-robo-harness.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L320) `README.md:320` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Robotics and hardware
- URL: https://github.com/grmkris/robo-harness
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> - [robo-harness](https://github.com/grmkris/robo-harness) - SO-101 arm workbench: a Jev decision runner picks bounded joint steps from typed candidate actions under a spend budget.

## What was checked

- Run-confirmed, GitHub API 2026-09-22: `grmkris/robo-harness`, 2 stars, SPDX none, push 2026-09-21, archived False, language TypeScript.
- API description: SO-101 robot-arm agent workbench: Bun/Effect coordinator, React workbench, Python LeRobot motor owner

## Role Jev plays

Jev's place is a discrete next action inside a control loop. Motors, setpoints, and safety interlocks are not the model. The list says: SO-101 arm workbench: a Jev decision runner picks bounded joint steps from typed candidate actions under a spend budget. This page did not trace the loop and did not remeasure the rate.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The launch post's vendor-reported frontier latency, 3–329 seconds end to end, does not fit a loop that has to tick at a few hertz. That range was not measured on this hardware. An LLM can still choose a slow, deliberative action outside the inner loop.

## If this were a script

Inference. A controller, a waypoint list, or a PID loop is the right instrument when the dynamics are known. It is the wrong instrument when the choice is semantic, such as whether an obstacle is something the policy must yield to. The list does not show which of those this project is.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
