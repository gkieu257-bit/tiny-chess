# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/gkieu257-bit/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/gkieu257-bit/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python. Original 0x88 alpha-beta search with PVS, late-move reductions, null-move pruning, quiescence search, transposition table, killer/history move ordering, repetition detection and a tapered material + piece-square evaluation — all under a fixed 150,000-node budget per move, so it is fully deterministic (no clock, no randomness). `main.py` is the packed entrypoint, produced by `makefun compress` from the readable source (uploaded with the entry bundle). Practice Elo 1,654 on the kit's trial-0 (5 wins, 1 loss).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kpjag36z&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
