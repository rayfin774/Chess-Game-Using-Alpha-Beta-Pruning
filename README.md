# Chess Game Using Alpha-Beta Pruning

This project is an implementation of a chess-playing artificial intelligence (AI) system using the Alpha-Beta Pruning algorithm in Python. It provides an interactive chess experience where a human player can compete against an intelligent AI opponent. The project demonstrates the application of game theory, search algorithms, and optimization techniques in artificial intelligence.

---

## Overview

The project uses the `python-chess` library to manage game logic and the Alpha-Beta Pruning algorithm to optimize decision-making. The AI evaluates each possible move using a heuristic evaluation function that measures material advantage and overall board position.

By using Alpha-Beta Pruning, the AI can search deeper game states efficiently by eliminating branches of the game tree that do not influence the final decision.

---

## Features

- Play chess against an AI opponent  
- Uses Minimax with Alpha-Beta Pruning for decision-making  
- Evaluates board positions using material value heuristics  
- Supports standard chess rules including checkmate, stalemate, and draws  
- Adjustable search depth for AI difficulty  

---

## Technologies Used

- **Language:** Python  
- **Libraries:** python-chess, sys  
- **Algorithm:** Minimax with Alpha-Beta Pruning  
- **Type:** Console-based AI Chess Engine  

---

## How It Works

1. The player makes a move in standard chess notation (e.g., `e2e4`).  
2. The AI analyzes all possible responses using the Alpha-Beta Pruning algorithm.  
3. The evaluation function assigns scores to board states based on material balance.  
4. The AI selects the best possible move to maximize its advantage.  
5. The process continues until checkmate, stalemate, or draw.  

---

## To Clone This Repository

```bash
git clone https://github.com/rayfin774/Chess-Game-Using-Alpha-Beta-Pruning.git
cd Chess-Game-Using-Alpha-Beta-Pruning
