# Maze Game (Python)

A console-based maze navigation game implemented in Python using a 2D grid.
The player moves through the maze using directional commands while respecting predefined movement constraints, with the goal of reaching the target cell.

---

##  Overview

This project represents a maze using a **2D list (matrix)** and allows the player to navigate through it step by step.
The maze is rendered using **ASCII characters**, and player movement is controlled via keyboard input.

The focus of this project is on:
- grid manipulation
- coordinate tracking
- enforcing movement rules
- maintaining game state

No external libraries are used.

---

##  Objective

Start from the initial position and reach the target cell by making valid moves within the maze structure.

---

##  Controls

| Key | Action |
|----|--------|
| `R` | Move Right |
| `L` | Move Left |
| `U` | Move Up |
| `D` | Move Down |

Invalid moves (out of bounds or against maze constraints) are rejected.

---

##  Concepts Used

- 2D lists (matrix representation)
- Row–column coordinate tracking
- Conditional logic for movement validation
- State mutation using list swapping
- Control flow with loops
- ASCII-based UI rendering

---

##  How to Run

```bash
python maze.py
