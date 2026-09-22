# Triage across 1,500 emails

[한국어](../../ko/projects/198-triage-across-1-500-emails.md) · [English](../../en/projects/198-triage-across-1-500-emails.md)

- List: [kraayenjon/awesome-jev](https://github.com/kraayenjon/awesome-jev/blob/22570dcd8662ae039860a1dfad7d7aec4aff8e15/README.md#L198) `README.md:198` at `22570dcd` (CC0). The fivetaku/awesome-jev fork was cloned at this commit.
- Section: Featured builds with real numbers
- URL: https://madewithjev.com/builds/inbox-triage-1500-emails
- Checked: 2026-09-22
- Depth: the list sentence and the front of the target. Not a source trace. Not a runtime test.

## What the list says it does

> | [Triage across 1,500 emails](https://madewithjev.com/builds/inbox-triage-1500-emails) | A full inbox sorted in one pass | ~1,500 emails | [X](https://x.com/ryanvogel/status/2100042788851101842) |

## What was checked

- Numbers printed in the list: ~1,500 emails. Author-reported (README.md:209). Not remeasured.

## Role Jev plays

Jev asks the same closed questions of every item in a pile the author already assembled. The list says: A full inbox sorted in one pass The figures next to that sentence are author-reported. README.md:209 says the list did not measure them. This study did not either.

## Setup

Setup on this page is only what the list sentence and the 2026-09-22 page front show. The repository source was not opened.

The list sentence and the front we read do not show an endpoint, a model id, a key variable, or a question schema for this item.

The official call shape is not this project's setup. The list's quick start (README.md:102-159) is `POST https://api.typesafe.ai/v1/systemone`, env `TYPESAFE_API_KEY`, Python `typesafe-sdk`, JS `@typesafe-ai/sdk`, and Choice, Noul, and Score against one state. On Vercel it is `experimental_evaluate` with id `typesafe-ai/jev`. That example was not run.

## If this were an LLM

Inference. An LLM can classify the same pile and will write more than a label. Cost and time scale with output length. The launch post's vendor-reported prices put LLM input at $0.20–$10 / MTok plus output, and Jev at $0.042 / MTok with output free. Applying those rates to this author's token counts would be a new calculation this study does not make.

## If this were a script

Inference. A script classifies a corpus only with rules you wrote, keyword lists or exact fields. It is the right tool for the columns that are already structured, and it will not generalize to the next phrasing.

## What this page does not do

No repository source, no tests, no remeasurement of author-reported numbers, and no full copy of a third-party README. Where the role goes past the list sentence, it is only a sentence checked on the page front. The LLM section and the script section are inference.
