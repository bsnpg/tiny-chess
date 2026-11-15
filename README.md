# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/bsnpg/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/bsnpg/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python: alpha-beta search with quiescence, check extensions, a transposition table, killer-move ordering, and a piece-square evaluation, built to play the make.fun tiny-chess-01 gauntlet.

## Run it

```sh
python3 -P -s main.py
```

The engine talks to the trial environment over HTTP (MAKEFUN_ENV_URL) and reads its brief from MAKEFUN_PROMPT_FILE.

---

Entered on [make.fun](https://make.fun/?ref=26zqsqqz&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
