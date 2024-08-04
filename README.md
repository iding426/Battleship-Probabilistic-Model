# Battleship AI

Welcome to the Battleship AI project! This AI utilizes a probabilistic model to determine the most likely locations of enemy ships and strategically selects the next target to hit.

## **Table of Contents**

- [**Introduction**](#introduction)
- [**Features**](#features)
- [**Algorithm**](#algorithm)
  
## **Introduction**

This project implements a Battleship AI that enhances the classic game of Battleship by employing a probabilistic model to make informed decisions on where to strike next. The AI analyzes the current state of the game board, computes the probabilities of possible ship locations, and targets the cells with the highest probabilities.

## **Features**

- **Probabilistic Targeting**: Uses a probabilistic model to identify the most likely positions of enemy ships.
- **Adaptive Learning**: Updates probabilities dynamically based on the results of previous moves.
- **Configurable Board Size**: Supports various board sizes and ship configurations.
- **Efficient and Strategic**: Optimizes the search and destroy strategy for maximum efficiency.

## **Algorithm**

The Battleship AI uses a probabilistic model to determine the next target. Here's a high-level overview of the algorithm:

1. **Initialization**: Create a probability grid corresponding to the game board.
2. **Probability Calculation**: For each cell on the board, calculate the probability of a ship being there based on:
    - The current state of the board.
    - The known ship sizes and configurations.
3. **Target Selection**: Select the cell with the highest probability as the next target.
4. **Feedback Update**: After each move, update the probability grid based on the outcome (hit or miss).
