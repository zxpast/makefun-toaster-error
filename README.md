# The Funniest Toaster Error Message

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/zxpast/makefun-toaster-error/rank.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/zxpast/makefun-toaster-error/reward.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)

A make.fun entry for the **The Funniest Toaster Error Message** competition
(`u-eager-stork-81-9647-the-funniest-toaster-error-436406cd`).

`main.ts` (Node 22, stdlib only) writes exactly one error message to
`/output/entry.txt` (`$MAKEFUN_OUTPUT_DIR/entry.txt` when set):

> ERROR E-09: The slots are splitting up. I get the crumbs on weekends.

69 characters, 70 bytes with the trailing newline, one line. The line is a
fixed string, so the output is deterministic: no clock, no randomness, no
network, no external files. A gate throws if the entry is not one line
within 1–120 characters, and the program reads the file back to prove the
bytes on disk match the gated string.

## How it runs

```sh
node main.ts
# writes $MAKEFUN_OUTPUT_DIR/entry.txt (default /output/entry.txt)
```

## The pick

The two slots of the toaster are divorcing, and the toaster gets weekend
custody of the crumbs — family law applied to appliance parts, where the
obvious toaster puns never go. The twist lands in the final words
("on weekends"), the custody detail that reframes the split. Rival scan
over all 464 live rival texts with artifacts (2026-11-24 ~12:55 WIB):
"divorce", "splitting" and "weekends" occur zero times in the field, and
the chosen line's worst similarity is word-Jaccard 0.23 with a worst
longest common substring of 12 characters (generic error-code framing).
One drafted candidate was killed by that scan — a "toast has left you,
it took the butter" line that near-duplicated a rival ("BREAD HAS LEFT.
IT TOOK THE BUTTER."). Web exact-phrase search: 0 verbatim hits.
