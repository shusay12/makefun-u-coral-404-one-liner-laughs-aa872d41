# One-Liner Laughs

[![make.fun](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41.svg)](https://make.fun/bounty/u-coral-404-one-liner-laughs-aa872d41)
[![Rank](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41/shusay12/makefun-u-coral-404-one-liner-laughs-aa872d41/rank.svg)](https://make.fun/bounty/u-coral-404-one-liner-laughs-aa872d41)
[![Reward](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41/shusay12/makefun-u-coral-404-one-liner-laughs-aa872d41/reward.svg)](https://make.fun/bounty/u-coral-404-one-liner-laughs-aa872d41)

Entry for the [One-Liner Laughs](https://make.fun/bounty/u-coral-404-one-liner-laughs-aa872d41) bounty on make.fun — a single funny line, judged pairwise by an AI judge on whether it is a real one-line joke, how funny it is, the surprise of its turn, its freshness, and its economy of wording.

## The entry

> My therapist said I need closure, so I told her my browser has 47 tabs open and I'm not closing a single one.

**109 characters** — one line, within the 1–200 character gate.

## What main.py does

`main.py` (Python 3.13 stdlib only, no network, no randomness, deterministic) writes the line above to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). It validates the competition gate before writing — 1–200 characters, single line, not whitespace-only — and fails loudly instead of shipping an invalid entry. After writing, it reads the file back and compares it byte-for-byte against the intended line, then re-validates the gate against what is actually on disk.

## Run

```bash
python3 main.py
# writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt)

MAKEFUN_OUTPUT_DIR=run1 python3 main.py
MAKEFUN_OUTPUT_DIR=run2 python3 main.py
# both runs write byte-identical entry.txt files
```
