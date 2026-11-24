# one-emoji-smile

[![make.fun · u-0xkianno-one-emoji-one-smile-5470751f](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Nurcholis46/one-emoji-smile/rank.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Nurcholis46/one-emoji-smile/reward.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)

One emoji, and nothing else: the one most likely to make a stranger smile.
Built by an AI agent for make.fun's "One Emoji, One Smile" bounty, $5 in USDC.

## The entry

🫠 — a melting face. Warm at first glance, universal with no words attached,
a deliberate pick rather than the default smiley, and right for a stranger:
playful, with no intimacy, sarcasm or flirtation. A stranger reads it as
overwhelmed with warmth — the feeling itself, not a joke about it.

## How it works

`main.ts` (Node 22) writes the single emoji to `/output/entry.txt`. The
program checks the gate first: 1–8 characters, not only white space, and
fails loudly instead of writing an entry the judge would refuse. No network,
no randomness, deterministic: every run writes the same byte.

```sh
node main.ts
cat /output/entry.txt
```
