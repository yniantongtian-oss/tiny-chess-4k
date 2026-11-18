# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yniantongtian-oss/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yniantongtian-oss/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a 4 KB `main.py` (Python 3.13 stdlib only).

- 10x12 mailbox board with piece lists and incremental
  material, PST, phase and Zobrist keys
- Tapered PeSTO evaluation, cached pawn structure (passed,
  doubled, isolated), bishop pair, rook files, king shield,
  endgame mop-up
- PVS alpha-beta with iterative deepening, aspiration
  windows, transposition table, null move, reverse futility,
  late move reductions, killers, history, check extension
- Quiescence search with captures, queen promotions and
  check evasions
- Fully deterministic: node budgets instead of clocks,
  seeded Zobrist keys, exact game-history repetition checks

`main.py` is the LZMA-packed build of the engine source.

<sub>Entered on [make.fun](https://make.fun/?ref=yq04c8zw&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
