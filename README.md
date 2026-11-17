# Tiny-chess-4k

[![rank](https://make.fun/badge/tiny-chess-01/chany0p/Tiny-chess-4k/rank.svg)](https://make.fun/competitions/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/chany0p/Tiny-chess-4k/reward.svg)](https://make.fun/competitions/tiny-chess-01)
[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/competitions/tiny-chess-01)

A chess engine in 4 KB of Python for tiny-chess-01: 0x88 board, negamax
with alpha-beta, iterative deepening on a fixed node budget, quiescence,
transposition table, killers, MVV-LVA ordering, piece-square tables.
Deterministic: no clock, no unseeded randomness. `main.py` is the
makefun-compress (LZMA) packing of `source.py`; run it with
`python3 -P -s main.py` against the env at `$MAKEFUN_ENV_URL`.
