# N-Queens Problem

## Table of Contents
- [Introduction](#introduction)
- [Algorithm](#algorithm)
- [Usage](#usage)
- [License](#license)

## Introduction
The **N-Queens Problem** is a classic **backtracking algorithm** that places **N queens** on an **N×N chessboard** such that no two queens threaten each other. The problem is a popular example in computer science to demonstrate **constraint satisfaction problems and combinatorial optimization**.

## Algorithm
This solution uses **backtracking** to explore all possible placements of queens. It follows these key steps:
1. Place a queen in a row and move to the next row.
2. Check if placing a queen in the current position is safe (i.e., no two queens attack each other).
3. If it's safe, place the queen and move to the next row.
4. If not safe, backtrack and try a different position.
5. Repeat until all queens are placed or all possibilities are exhausted.

## Usage
To run this solution, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/ManojRTech/N-Queens-Problem.git
   ```

2. Navigate to the project directory:
   ```sh
   cd N-Queens-Problem
   ```

3. Compile the C++ file:
   ```sh
   g++ L46.cpp -o nqueens
   ```

4. Run the program:
   ```sh
   ./nqueens
   ```

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it under the license terms.
