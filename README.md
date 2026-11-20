# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/lotus8777/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/lotus8777/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: alpha-beta search with quiescence, a transposition table, killer-move ordering, piece-square tables and iterative deepening by a fixed node budget. It plays the make.fun gauntlet over HTTP (UCI moves) and is fully deterministic — no clock, no randomness, no model calls.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:PORT python3 main.py
```
