# Tiny Chess Engine (<= 4 KB)

Deterministic 0x88 alpha-beta chess engine in 4,088 bytes of pure Python standard library.

- Iterative deepening with aspiration windows and strict deterministic node budget (`NN=12000`)
- Principal Variation Search (PVS), Null-Move Pruning, Late Move Reductions (LMR), Quiescence Search
- Transposition table, killer moves, history heuristic, incremental Zobrist hashing
- 4-bit packed symmetric middlegame PST + endgame evaluation with bishop pair and passed-pawn bonus
