# Connect Four AI

A Connect Four game developed in Python using Pygame, featuring an AI opponent powered by the Minimax algorithm with Alpha-Beta Pruning.

## Overview

This project is an implementation of the classic Connect Four board game where a human player competes against an intelligent AI agent.

The main focus of this project is the implementation of the Minimax decision-making algorithm and Alpha-Beta Pruning to create a competitive AI opponent capable of evaluating board positions and selecting optimal moves.

## Features

* Interactive graphical interface using Pygame
* Human vs AI gameplay
* Intelligent AI opponent
* Minimax algorithm implementation
* Alpha-Beta Pruning optimization
* Board evaluation heuristic
* Win detection system
* Multi-round score tracking
* Visual game-over screen

## Technologies Used

* Python
* Pygame
* NumPy

## AI Implementation

The AI player uses:

* Minimax Search Algorithm
* Alpha-Beta Pruning
* Heuristic Board Evaluation Function
* Move Simulation and State Exploration

The core AI logic was implemented in the `minimax()` function, where game states are recursively explored to determine the best possible move while reducing unnecessary search branches using Alpha-Beta Pruning.

## Installation

Clone the repository:

```bash
git clone https://github.com/haniehmz/Connect_Four_game.git
```

Move to the project directory:

```bash
cd Connect_Four_game
```

Install dependencies:

```bash
pip install pygame numpy
```

Run the game:

```bash
python main.py
```

## Game Rules

1. Players take turns dropping pieces into columns.
2. Pieces fall to the lowest available position.
3. The first player to connect four pieces horizontally, vertically, or diagonally wins the round.
4. The game tracks scores across multiple rounds.

## Screenshots

<img width="872" height="917" alt="pic1" src="https://github.com/user-attachments/assets/6afd9df5-b4b7-4bb5-9f1e-6fa5483117c8" />

<img width="873" height="910" alt="pic2" src="https://github.com/user-attachments/assets/be10f46f-676a-4563-86d8-5663ec758ed3" />

<img width="876" height="920" alt="pic3" src="https://github.com/user-attachments/assets/9047a443-9485-431c-8a30-f4fa3347997d" />

<img width="622" height="413" alt="pic4" src="https://github.com/user-attachments/assets/887d8020-ff80-4cc8-8028-e348bbe1457a" />
