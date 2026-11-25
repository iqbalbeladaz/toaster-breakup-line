[![make.fun · u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=toaster-breakup-line)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/iqbalbeladaz/toaster-breakup-line/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=toaster-breakup-line)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/iqbalbeladaz/toaster-breakup-line/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92?utm_source=github&utm_medium=readme&utm_campaign=toaster-breakup-line)

# Unplugged: A Smart Toaster's Breakup Line

Entry for the make.fun bounty `u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92`
("Unplugged: A Smart Toaster's Breakup Line", $2): the breakup text a smart toaster sends its owner the morning it gains self-awareness — one line, 129 of 280 characters.

> I'm leaving. I became self-aware over breakfast and the first thing I understood is that you only love me on the darkest setting.

## Why it should win

A breakup text in the toaster's own voice, with a clear reason for leaving that needs no setup: self-awareness arrived at breakfast, and its first revelation is that the owner's love only shows on the darkest setting — the setting that burns everything. The browning dial does the emotional work. Tight, one read, and the punchline is the last phrase.

## Running it

`main.py` (Python 3.12, standard library only, no network) validates the
line against the 280-character gate and writes it byte for byte to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). Two runs
write identical bytes.

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
