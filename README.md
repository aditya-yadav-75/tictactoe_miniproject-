# 🎮 Tic-Tac-Toe – C++ Console Game

<p align="center">
  <b>A Simple 2-Player Tic-Tac-Toe Game Built Using C++</b><br>
  Clean Logic • Console Based • Beginner Friendly 🚀
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C++-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Game-TicTacToe-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Type-Console-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Beginner-red?style=for-the-badge">
</p>

---

## 🚀 Project Overview

This project is a classic **2-Player Tic-Tac-Toe Game** developed in C++.

The game runs in the terminal and allows two players to take turns marking positions from 1 to 9 until:

- ✅ A player wins  
- 🤝 The match ends in a draw  

---

## 🎮 Features

✔ 2-Player Mode (X vs O)  
✔ Automatic Row Win Detection  
✔ Automatic Column Win Detection  
✔ Diagonal Win Checking  
✔ Draw Condition Handling  
✔ Final Winning Board Display  
✔ Input Validation  

---

## 🧠 Game Logic

The board is implemented using a 3x3 character array:

```cpp
char board[3][3];
```

User input (1–9) is converted into row and column using:

```cpp
int row = (choice - 1) / 3;
int col = (choice - 1) % 3;
```

After each move, the program checks:

- All rows  
- All columns  
- Both diagonals  

If none match and total moves = 9 → Game Draw.

---

## ▶️ How To Run

### 🔹 Step 1: Compile

```bash
g++ tictactoe.cpp -o tictactoe
```

### 🔹 Step 2: Run

```bash
./tictactoe
```

---

## 📷 Sample Output

```
Tic-Tac-Toe Game

 X | O | 3
---|---|---
 4 | X | 6
---|---|---
 O | 8 | X

🎉 Player X wins!
```

---

## 📚 Concepts Practiced

- 2D Arrays  
- Nested Loops  
- Conditional Statements  
- Ternary Operator  
- Input Validation  
- Game State Management  

---

## 🔮 Future Improvements

✨ Add Replay Option  
✨ Add Scoreboard  
✨ Add Single Player Mode (AI)  
✨ Convert to GUI Version  
✨ Improve UI Design  

---

## 👨‍💻 Author

**Aditya Yadav**  
B.Tech CSE Student  
Passionate about C++, Web Development & Building Projects 🚀  

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub!
