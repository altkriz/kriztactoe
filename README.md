# 🎮 Kriz-Tac_Toe | Unbeatable Tic-Tac-Toe with AI  

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

A sleek, modern Tic-Tac-Toe game built with pure HTML, CSS, and Vanilla JavaScript. But there's a twist—**you can never win**. 

The AI opponent is powered by the mathematically flawless **Minimax Algorithm**, meaning the best possible outcome you can achieve is a Tie. 

## ✨ Features

- **🤖 Unbeatable AI Opponent:** Uses the recursive Minimax algorithm to look ahead and calculate every possible future outcome.
- **🌌 Modern UI/UX:** Features a beautiful dark/neon theme with Glassmorphism (frosted glass) effects.
- **💫 Smooth Animations:** Includes satisfying "pop-in" entry animations for X's and O's, and a glowing pulse effect for the winning row.
- **📊 Real-time Scoreboard:** Keeps track of your desperate attempts to win.
- **⚡ Zero Dependencies:** Built completely from scratch. No React, no external libraries, just pure frontend code.

## 🧠 How the AI Works (The Minimax Algorithm)

Unlike simple Reinforcement Learning that requires thousands of practice games to get smart, this AI uses the **Minimax Algorithm**. 

Before making a move, the AI plays out *every single possible remaining move in the game* in its "head" (creating a decision tree). It assumes you will play perfectly, and evaluates the final board states:
- **+10 points** if the AI wins.
- **-10 points** if the Human wins.
- **0 points** for a Tie.

It then works backward to choose the move that maximizes its own score while minimizing yours. **Result: It is mathematically impossible to defeat.**

## 🚀 How to Play

Since this project has zero external dependencies, running it is incredibly simple:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/altkriz/kriztactoe.git
