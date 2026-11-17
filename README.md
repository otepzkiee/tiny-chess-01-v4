[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/otepzkiee/tiny-chess-01-v4/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/otepzkiee/tiny-chess-01-v4/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01 — 4 KB Python chess engine (v4)

A complete chess engine in a single `main.py` under 4 KB: 0x88 board,
alpha-beta search with PVS, transposition table, quiescence search with
delta pruning, check extensions, late move reductions, iterative
deepening and a fixed budget of 100,000 nodes per move. Evaluation is
material plus hand-tuned piece-square tables, a bishop-pair bonus and an
endgame king table. The readable source is `engine.py`; `pack.py`
minifies it, compresses it with lzma and writes the self-extracting
`main.py` that plays.

Local practice results against the kit's house engines: 8.0 points in
18 games across the three practice trials, Elo approximately 1,221 — the best
of four engine variants tested head-to-head for this entry.

Built for the make.fun tiny-chess-01 bounty competition.
