# Tiny Chess Engine

A 4 KB chess engine in a single Python file (`main.py`, stdlib only):
0x88 board, negamax alpha-beta with iterative deepening, quiescence
search, transposition table, killer moves and MVV-LVA ordering.

Written from scratch for the make.fun tiny-chess-01 competition.

Run it against the competition harness (`MAKEFUN_ENV_URL` must point at
the environment server); the engine speaks the harness JSON protocol.
