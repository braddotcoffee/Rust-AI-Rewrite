# Rust-AI-Rewrite

A rewrite of the repository AI-Project2 in Rust

---

This simple AI plays a modified version of the game Gomoku. We use a simple minimax algorithm with alpha-beta pruning
combined with a simple heuristic for the value of a board state in order to decide on moves. There is a `referee` which
organizes the game, managing the turn system via a file-based API.


