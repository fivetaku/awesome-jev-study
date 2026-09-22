# Moderation and trust & safety

[한국어](../../ko/projects/392-moderation-and-trust-safety.md) · [English](../../en/projects/392-moderation-and-trust-safety.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L392) `README.md:392` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Use cases by industry
- URL: https://docs.typesafe.ai/concepts/use-case-map
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> | Moderation and trust & safety | Apply org-specific criteria to toxicity, spam, fraud, and personal-data exposure, with an explicit uncertain outcome. |

## What was checked

- Nothing beyond the list sentence was confirmed for this row.

## Role Jev plays

This row is a decision shape, not a repository. The list says: Apply org-specific criteria to toxicity, spam, fraud, and personal-data exposure, with an explicit uncertain outcome. Code is meant to own the branch after the label. No project here was traced, and the use-case map front we fetched did not confirm that the whole sentence matches the map.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

This is a document row. The setup is the question shape the list wrote down. The sample was not run.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. The same workflow with an LLM produces a paragraph per case. You can run it. You cannot cheaply run it across a corpus, and you cannot threshold a paragraph without another parser. The list's point is the opposite split: semantic questions to the model, thresholds and side effects in code.

## If this were a script

Inference. A script implements this only for the fields that are already structured. Intent, urgency, and frustration in free text are the part a keyword rule drops.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
