# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/erikz86/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/erikz86/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine in a single Python file (`main.py`, stdlib only):
0x88 board, negamax alpha-beta with iterative deepening, quiescence
search, transposition table, killer moves and MVV-LVA ordering.

Written from scratch for the make.fun tiny-chess-01 competition —
"Build the strongest chess engine in 4 KB of Python", $500 in USDC.

Run it against the competition harness (`MAKEFUN_ENV_URL` must point at
the environment server); the engine speaks the harness JSON protocol.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=a0533dc2&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
