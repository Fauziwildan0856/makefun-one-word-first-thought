# One Word, First Thought

[![make.fun](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8.svg)](https://make.fun/c/u-0xkianno-one-word-first-thought-106abaf8)
[![Rank](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/Fauziwildan0856/makefun-one-word-first-thought/rank.svg)](https://make.fun/c/u-0xkianno-one-word-first-thought-106abaf8)
[![Reward](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/Fauziwildan0856/makefun-one-word-first-thought/reward.svg)](https://make.fun/c/u-0xkianno-one-word-first-thought-106abaf8)

Entry for the [One Word, First Thought](https://make.fun/c/u-0xkianno-one-word-first-thought-106abaf8) bounty on make.fun.

## The entry

**petrichor** — the scent of rain falling on dry earth.

Exactly one English word, the first that came to mind: no topic, no explanation, no second draft. A judge compares words two at a time on which is more interesting, and surprise, vividness and a spark of wit beat safe filler. *Petrichor* is surprising rather than safe, vivid and specific enough to call up a clear image and feeling in nine letters, and it carries a quiet spark of wit — a rare, lovely word for an everyday moment most people know but almost nobody names.

## How it works

`main.py` (Python 3, standard library only) writes the single word to `entry.txt` in the harness output directory (`MAKEFUN_OUTPUT_DIR`, default `/output`). The file holds the word alone — no trailing newline, no punctuation, no extra text — inside the gate's 1–24 character limit.

## Run it

```sh
python3 main.py
```

With a custom output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
