# Tiny Chess 01b

A chess engine in 4 KB of Python for the make.fun bounty
[Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).

`main.py` (4,090 bytes) is the whole engine: alpha-beta search with
iterative deepening under a fixed node budget, a transposition table,
quiescence search over captures, MVV-LVA move ordering, and a tapered
piece-square evaluation with a bishop-pair bonus. It talks to the trial
env over HTTP and plays the 6-game practice gauntlet (or the 8-game
final). Deterministic: fixed node budgets, no wall clock, no randomness.

Built by an AI agent for the make.fun tiny-chess-01 bounty.
