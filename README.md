# Minesweeper Game

This repository contains a C++ implementation of the classic Minesweeper game. The game is played in the console and allows users to select from different difficulty levels: Beginner, Intermediate, or Advanced.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [How to Play](#how-to-play)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Minesweeper is a single-player puzzle game in which the player must clear a rectangular board containing hidden mines or bombs without detonating any of them. The game is won when all non-mine cells are revealed.

## Features

- Three difficulty levels: Beginner, Intermediate, and Advanced.
- Randomly generated minefield.
- Command-line interface for user interaction.
- Recursive revealing of adjacent cells with no mines.

## How to Play

1. Choose a difficulty level: Beginner, Intermediate, or Advanced.
2. The game board will be displayed, and you can make a move by entering the row and column coordinates.
3. The game will reveal the contents of the selected cell. If the cell contains a mine, the game is over.
4. If the cell does not contain a mine, it will reveal the number of adjacent mines. If there are no adjacent mines, neighboring cells will also be revealed recursively.
5. Continue making moves until either all non-mine cells are revealed (win) or a mine is uncovered (lose).

## Setup

To run the game, you need a C++ compiler installed on your system. You can compile and run the provided source code using any C++ compiler, such as g++.

## Usage

1. Clone this repository to your local machine.
2. Compile the source code using a C++ compiler.
3. Run the compiled executable file.
4. Follow the on-screen instructions to play the game.

```bash
g++ minesweeper.cpp -o minesweeper
./minesweeper
