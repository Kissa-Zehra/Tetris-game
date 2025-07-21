# 🎮 Terminal Tetris Game in C

![Language](https://img.shields.io/badge/Language-C-blue.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

A classic **Tetris** implementation that runs entirely in the terminal, written in C. Enjoy traditional gameplay with falling tetrominoes, line clearing, scoring, and intuitive keyboard controls.

---

## 📋 Description

This is a **terminal-based Tetris game** developed in C as part of a group project. It replicates the core mechanics of the original: pieces fall from the top, you move and rotate them to fill horizontal lines, which then clear to gain points. The game supports increasing speed, real-time input, and basic scoring.

---

## 🧩 Features

- 🔷 **Tetromino Shapes**: All 7 standard Tetris shapes (I, O, T, S, Z, J, L)
- 🔄 **Rotations and Movement**: Left/Right, Down, and Rotate  
- 🎯 **Line Clearing** with scoring  
- ⏱️ **Level Progression**: Speed increases every few lines  
- 🕹️ **Keyboard Controls**: Designed for smooth gameplay in the terminal  
- 🧠 **Next-piece Preview** (optional, if implemented)

---

## 🛠️ How to Compile & Run

### ✅ Requirements

- C compiler (e.g., GCC)
- Unix-like Terminal or Windows Console

### 💻 Build Instructions

```bash
# Clone your repository or navigate to the project folder
gcc main.c -o tetris -lncurses     # If using ncurses
# OR
gcc main.c -o tetris               # Without ncurses

# Run the game
./tetris
Replace main.c with your actual C source file name(s).
If using ncurses, ensure the development package is installed: sudo apt install libncurses5-dev (Ubuntu/Debian).
```

## 🎮 Controls

| Key        | Action          |
|------------|-----------------|
| ← / →      | Move left/right |
| ↓          | Soft drop       |
| Space      | Hard drop       |
| ↑ or Z     | Rotate piece    |
| P          | Pause game      |
| Q          | Quit game       |

---

## 🧠 How to Play

1. Start the game.
2. A tetromino falls from the top.
3. Use **left/right arrows** to move, **up arrow** or **Z** to rotate.
4. Press **↓** to move down faster or **Space** for a hard drop.
5. Clear full horizontal lines to earn points.
6. Every 10 lines or so, the **level increases**, speeding up the fall.
7. Game ends when new pieces can't fit at the top.

## 📁 File Structure

```bash
tetris/
├── main.c # Game entry point
├── tetromino.c/.h # Tetromino templates and logic
├── game.c/.h # Game loop and rendering
├── input.c/.h # Input handling
├── Makefile # Build automation (if used)
├── README.md # Project documentation
└── LICENSE # MIT License file
```

---

## 🧭 Why this Project?

- ✅ Designed for learning C fundamentals and structured programming  
- ✅ Provides hands-on experience with **real-time input handling** and **game loops**  
- ✅ Great for practicing memory management, arrays, and keyboard interaction  

---

## 📂 License

This project is released under the **MIT License**.  
See [LICENSE](LICENSE) for full details.
