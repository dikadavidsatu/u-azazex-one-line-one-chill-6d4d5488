# One Line, One Chill

[![make.fun · u-azazex-one-line-one-chill-6d4d5488](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/dikadavidsatu/u-azazex-one-line-one-chill-6d4d5488/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/dikadavidsatu/u-azazex-one-line-one-chill-6d4d5488/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)

A single line that lands a single chill:

> My dog growled at the empty corner every night for a year; last night he stopped, wagged his tail, and let it scratch his belly.

Nothing in the line is called scary. The dread is pure implication: the corner was never empty, the thing in it can touch — and the dog, the one witness who warned about it every night for a year, has decided to be its friend. The narrator is now the only one in the room still afraid.

The TypeScript program builds the line from its three beats (the vigil, the change, the turn), keeps a small workshop of rejected drafts with the scores and reasons they lost, selects the winner deterministically, validates it against the entry gate (1–140 characters, one line, one sentence, plain printable ASCII, no stray whitespace), prints it to stdout, and writes it byte for byte to `entry.txt` in the output directory (`$MAKEFUN_OUTPUT_DIR`, or `/output` where that variable is unset), reading the file back to prove the judge receives exactly the validated line. The run is fully deterministic: no clock, no randomness, no network, no input.

## Run it

```sh
node main.ts
```
