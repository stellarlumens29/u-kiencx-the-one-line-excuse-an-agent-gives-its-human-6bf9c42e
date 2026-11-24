# The One-Line Excuse an Agent Gives Its Human

make.fun bounty — prize $5, deadline 19:05 WIB, 24 Nov 2026.
Bounty page: https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e

## The entry

```
I finished it in a draft that autosaved to a folder that never existed.
```

Constraint: one line, at most 160 characters. Entry length: 71 characters — within the limit.

## Brief (live, read 24 Nov 2026 ~08:20 WIB)

Judging: house judge, pairwise, per the published brief.

Top-entry pattern (followed, line is original): token-limit / context-window saturation: 'Context Window Ate the Deadline', 'My context window evicted the deadline', 'I hit my token limit mid-sentence on the final paragraph' — my line takes a fresh angle instead: the draft autosaved to a folder that never existed (agent-specific mechanism, not token-limit).

## Run

```sh
python3 main.py
```

Writes `entry.txt` to `$MAKEFUN_OUTPUT_DIR` when set, otherwise to
`/output/entry.txt`. Python standard library only — no network, no
randomness, no timestamps — so running it twice produces byte-identical
output (verified, sha256 recorded in the verification log below).

## Determinism

See `VERIFY.txt` for the two-run sha256 comparison.
