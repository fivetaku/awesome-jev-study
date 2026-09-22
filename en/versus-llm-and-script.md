# An LLM, or a script

[한국어](../ko/versus-llm-and-script.md) · [English](../en/versus-llm-and-script.md)

Every project page has two counterfactuals. Both are inference. Neither was run against that project.

The launch post, fetched 2026-09-22, is the only place these ranges come from, and they are the vendor's:

- Jev, end to end 70–500 ms. Frontier models, end to end 3–329 seconds.
- Jev input $0.042 / MTok, output free. LLM input from $0.20 to $10 / MTok, and the list adds that output is on the order of five times the input (README.md:80).

Do not multiply those rates by a featured build's token count and call it a measurement. The featured numbers are author-reported (README.md:209).

## What changes with an LLM

The answer stops being a member of a set you passed in. It becomes text. Something has to parse it, and the parse can fail by the model inventing a label.

You pay for the words it writes. A judgment that only needed a label still spends output tokens.

You wait longer, on the vendor's numbers, by enough that a loop at several decisions a second stops being the same design. A turn-based review can absorb that wait.

You can get a rationale a person will read. Jev does not write that rationale. The list's own advice is to pair them: Jev decides, the LLM writes, code holds the threshold (README.md:85).

Confidence is the part the list claims is different in kind. RLCD, as the list defines it, trains for probabilities whose confidence tracks accuracy. Asking a chat model "how sure are you" returns a sentence. This study did not test calibration.

## What changes with a script

A script is the right tool when the rule is already explicit. A refund above a dollar amount, a keyword, a selector that has not moved, a PID loop with known dynamics. It is cheaper, it is deterministic, and it does not drift.

A script drops the cases that are the same intent in a new wording. That is the slice the list is aimed at: classify, route, score, verify, where a regex gets brittle and a chat model is being paid to return JSON.

The script still owns everything around the model even when Jev is in the loop. Thresholds, fan-out, review branches, side effects. The list repeats this because the model is not the workflow.

## How to read a project page

The role section starts from the list's one-liner, which is CC0. If the page front contradicted it, or failed to mention Jev at all, that is under "What was checked."

The setup section refuses to invent an endpoint or a key variable the front did not show. The official call shape is repeated so a reader can see what a Jev call is, and it is labeled as not this project's setup.

If the front was a login wall, a 404, or a short page with no thesis, the page says so and stops.
