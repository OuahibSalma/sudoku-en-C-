# sudoku-en-C-
# Sudoku Game with Linked Lists

## Overview

This project implements a Sudoku game using linked lists in C. The Sudoku game involves creating a grid, generating puzzles, and allowing users to play by filling in the empty spaces. The use of linked lists facilitates the management of the Sudoku grid and provides flexibility for various operations.

## Features

- **Linked Lists:** The project heavily utilizes linked lists to manage the Sudoku grid. This includes functions for adding elements, displaying the grid, and memory management.

- **Difficulty Levels:** The main function prompts the user to choose a difficulty level, influencing the complexity of the generated Sudoku puzzle.

- **Random Number Generation:** The `random` function from the `math.h` library is employed to generate random numbers, determining the initial Sudoku grid and the placement of empty spaces.

- **User Interaction:** The program engages the user by displaying the Sudoku grid with some spaces already filled. It prompts the user if they want to see the solution and then reveals the solution stored in a linked list.

## Algorithms

Two main algorithms are explored in this project:

1. **Matrix Transformation:** Some classmates used a function to transform a linked list into a matrix. While this approach is valid, it encountered challenges, with a significant percentage of generated Sudoku puzzles having no solution and requiring substantial processing time.

2. **Linked List Approach:** The preferred approach involves generating a Sudoku puzzle, hiding the solution in a linked list, and then creating another linked list with empty spaces for user interaction. This approach addresses the issues faced by the matrix transformation method.

## Project Structure

- `makefile`: The makefile for building the project.
- `library.c`: A library containing all the necessary functions for managing linked lists and Sudoku operations.
- `header.h`: The header file with function prototypes.
- `main.c`: The main file where the Sudoku game is implemented.

## Usage

To compile and run the program, use the provided `makefile`. For example:

```bash
make
./sudoku_game
