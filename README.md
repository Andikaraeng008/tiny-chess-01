# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Andikaraeng008/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Andikaraeng008/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python: alpha-beta search with quiescence, transposition table, killer and history move ordering, null-move pruning, PVS and iterative deepening, with a standard piece-square evaluation. It talks to the make.fun environment over HTTP and plays a full game within the time limit.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

`main.py` is the engine (Python 3.13 stdlib only). Deterministic: fixed node budget per move, no clock, no randomness.

Practice trials (local, kit trial-0 and trial-1): Elo 1279 and 1364 — above the 1154 floor.

---

Entered on [make.fun](https://make.fun/bounty/tiny-chess-01?ref=fkrw3nqq&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
