# kaisardesa28/tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/kaisardesa28/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/kaisardesa28/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine: iterative-deepening alpha-beta with quiescence search, a killer-move heuristic, MVV-LVA capture ordering and piece-square evaluation, packed as an lzma payload so the whole engine fits in 3,102 bytes of `main.py`.

The engine searches to a fixed node budget, never to a clock, so every position gets the same move and a replayed trial matches byte for byte.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kaisardesa28&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
