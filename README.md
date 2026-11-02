# Sliding Boulder Puzzle Engine

The game logic for a sliding-block puzzle, written in Java. Pieces can cover multiple cells, and the engine enforces the rules of the board. A recursive backtracking solver finds solution paths.

**Tech stack:** Java, algorithms, backtracking

## What I Built

- **Puzzle-state transitions for multi-cell pieces**, enforcing board boundaries, collision rules, and atomic movement constraints (a move either fully succeeds or leaves the board unchanged).
- **Recursive backtracking solver** that explores valid game states and enumerates possible solution paths.
- **Undo and reset** that preserve the previous board state without corrupting the active game state.

## Skills Demonstrated

- Modeling game state so moves are atomic and reversible
- Writing recursive backtracking search
- Keeping saved states separate from the active state to avoid corruption
- Object-oriented design in Java

## About This Repository

This was a course project at Iowa State University. To respect the course's academic integrity policy, the source code is not published. This page describes what I built and what I learned.
