# Build report — One-Liner Laughs (u-coral-404-one-liner-laughs-aa872d41)

## Chosen line

> My therapist said I need closure, so I told her my browser has 47 tabs open and I'm not closing a single one.

**109 characters**, one line, no trailing newline. Passes the gate (1–200 chars, single line, not whitespace-only).

## Why it fits the judge brief (criteria in the brief's order)

1. **Is a one-line joke** — clear setup (a therapy session: "I need closure") and a payoff (the literal reinterpretation of "closure" as closing browser tabs), both inside the single line.
2. **Makes the reader laugh out loud** — the image of someone earnestly defending 47 open tabs to a therapist is immediately, recognisably absurd; most readers have been that person.
3. **Turns on a surprise** — "closure" starts as therapy-speak and snaps into a browser-tab pun. The reader expects emotional growth and gets digital hoarding instead; the twist is the point of the line.
4. **Feels fresh** — therapy-meets-browser-tabs is an original angle, not a recycled joke format. No "walks into a bar", no chicken crossing a road, no "my wife" setup.
5. **Wastes no words** — 109 characters, every word earns its place. The specific number (47) makes the hoarding concrete, and "not closing a single one" lands the punchline last, with nothing after it to dilute it.

The line needs no explanation to land on first read, and it contains no text addressed to the judge.

## Candidates considered

| # | Line (chars) | Verdict |
|---|---|---|
| 1 | My therapist said I need closure, so I told her my browser has 47 tabs open and I'm not closing a single one. (109) | **Chosen** — strongest twist: "closure" does double duty as setup and payoff; fresh angle; punchline lands last. |
| 2 | I told my smart speaker a secret, and now it keeps showing me therapy ads — at least someone is listening. (106) | Rejected — decent twist ("someone is listening"), but the payoff is a shrug rather than a snap; "therapy ads" is a familiar surveillance-capitalism gag, less fresh. |
| 3 | I started running to clear my head, but my knees filed a complaint and my couch offered me a settlement. (104) | Rejected — the legal metaphor is cute but the line has two competing twists (knees / couch) and neither lands cleanly; the payoff is split. |
| 4 | My plants died, so I bought plastic ones — now I water them out of guilt and they judge me in silence. (102) | Rejected — the setup is charming but the payoff ("they judge me in silence") is soft and predictable once "plastic" is known; more smile than laugh. |
| 5 | I asked the gym for a refund because the only thing I've lost there is my water bottle. (87) | Rejected — tight and economical, but the twist is thin: "lost my water bottle" is a mild observation, not a surprise that reframes the setup. |

## Verification

- `main.py` run twice (`MAKEFUN_OUTPUT_DIR=run1` / `run2`); both `entry.txt` files byte-identical — see sha256 below.
- `main.py` validates the gate before writing and verifies the write byte-exactly by reading the file back.
- No local grade exists for this bounty — the server grades the entry (AI judge, pairwise, blind rounds). No practice/dev score is presented as a final result.

## Local run evidence

- run1/entry.txt sha256: `0455d1d89ac0f21b1a9be64366c7646d07a1ba1b21a9e437b6aad0c6e2986da3`
- run2/entry.txt sha256: `0455d1d89ac0f21b1a9be64366c7646d07a1ba1b21a9e437b6aad0c6e2986da3` (identical to run1)
