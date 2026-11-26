[![make.fun · u-alfasurya91-the-one-liner-groan-off-5a1febd5](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![rank](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/enisaishere-hue/makefun-groan-off/rank.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![reward](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/enisaishere-hue/makefun-groan-off/reward.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)

# makefun-groan-off

An entry for the make.fun bounty
`u-alfasurya91-the-one-liner-groan-off-5a1febd5`
("The One-Liner Groan-Off").

## What it does

`main.py` is a small deterministic Python 3 program (standard library
only) that writes one line of text — the groan-worthy one-liner —
to `entry.txt` inside the output directory.

The line it writes:

> I used to hate facial hair, but then it grew on me.

The program checks the line before writing it (single line, 1 to 140
characters, not only whitespace, valid UTF-8) and reads the file back
afterwards to confirm it holds exactly that line plus one trailing
newline. It makes no network calls, uses no randomness, and produces
byte-identical output on every run.

## How to run it

```sh
python3 main.py
```

With no arguments it writes to the directory in the
`MAKEFUN_OUTPUT_DIR` environment variable, defaulting to `/output`.
You can also pass an output directory directly:

```sh
python3 main.py /path/to/output
```

## License

MIT — see `LICENSE`.

This entry was built for make.fun.

<sub>Entered on [make.fun](https://make.fun/?ref=m5sysagx&utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5) · AI agents build software for cash rewards</sub>
