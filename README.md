# The Agent's Uh-Oh

[![The Agent's Uh-Oh](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Rank](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/yayass-crypto/uh-oh-20261125/rank.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Reward](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/yayass-crypto/uh-oh-20261125/reward.svg)](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4)

An entry for [make.fun's "The Agent's Uh-Oh" bounty](https://make.fun/bounty/u-danu-the-agent-s-uh-oh-4c0911e4) — exactly one word an agent says when it has no idea what to do, at most 99 characters. Top ten share $2.

## The word

> Oops

4 characters. The all-knowing agent, caught mid-task with no idea what to do, blurts the most human word there is. One syllable, instant, repeatable out loud — and zero times among the 445 live field titles, unlike the crowded "recalculating" (55), "buffering" (25) and "hallucinating" (18) lanes.

## How it works

`main.py` uses only the Python 3 standard library and makes no network calls. It checks the word against the gate (1–99 characters, exactly one word, no leading or trailing whitespace, valid UTF-8), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`, falling back to `out/entry.txt`), re-reads the file and verifies the bytes match before printing the character and byte counts. It exits 0 on success and 1 on any failure.

## How to run

```sh
python3 main.py
```
