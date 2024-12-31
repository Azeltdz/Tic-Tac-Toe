# Tic Tac Toe in C++

![Tic Tac Toe Banner](https://via.placeholder.com/800x200.png?text=Tic+Tac+Toe+Game)  
_A simple console-based implementation of the classic Tic Tac Toe game._

## 🎮 Features
- **Two-player mode**: Player 1 and Player 2 alternate turns.
- **Dynamic board updates**: The game board updates after every move.
- **Win Detection**: Detects when a player wins or when the game ends in a draw.
- **Classic Console Style**: Simple and nostalgic user interface.

---

## 🛠️ Code Overview

### Language Used:
- **C++**

### Key Functions:
1. **`checkwin()`**: Determines the game status (win, draw, or continue).
2. **`board()`**: Displays the current game board.

### Core Gameplay Loop:
- Players take turns selecting positions.
- The board updates with their respective symbols (`X` for Player 1 and `O` for Player 2).
- The game checks for winning conditions or a draw after every move.

---

## 🚀 Getting Started

### Prerequisites:
- A C++ compiler (e.g., GCC, Clang, or Visual Studio).

### Steps to Run:
1. **Clone this repository:**
    ```bash
    git clone https://github.com/yourusername/tic-tac-toe.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd tic-tac-toe
    ```
3. **Compile the program:**
    ```bash
    g++ -o tictactoe tictactoe.cpp
    ```
4. **Run the executable:**
    ```bash
    ./tictactoe
    ```

---

## 📋 Game Rules
1. The game is played on a 3x3 grid.
2. Players take turns entering a number (1-9) corresponding to the position on the grid.
3. The first player to align three symbols (horizontally, vertically, or diagonally) wins.
4. If all 9 cells are filled without a winner, the game ends in a draw.

---

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

### Guidelines:
- Use descriptive commit messages.
- Format code properly.
- Ensure compatibility with standard C++ compilers.
---

## 💡 Acknowledgments
- Inspired by the classic Tic Tac Toe game.
- Developed by **[Azelt](https://github.com/Azeltdz)**.

---

## 🌟 Support
If you like this project, give it a ⭐ on [GitHub](https://github.com/Azeltdz/Tic-Tac-Toe)!

