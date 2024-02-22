# Chess Position Generator and Analysis

This project aims to generate chess positions based on the specified number of pieces, analyze the generated positions, and find the three best moves within each position.

## Features:

**Chess Position Generation:**
   - Generate random chess positions with a specified number of pieces.
   - The positions include a variety of pieces, such as pawns, rooks, bishops, knights, kings, and queens.
   - Positions are generated within the bounds of standard chess rules and configurations.

**Position Analysis:**
   - Analyze the generated chess positions to determine the best moves available.
   - Implement algorithms to evaluate potential moves based on their impact on the game state.
   - Assess threats, captures, and strategic advantages/disadvantages within each position.

**Best Move Identification:**
   - Identify and rank the three best moves within each generated position.
   - Evaluate moves based on their point value, considering factors such as capturing opponent pieces, threatening the opponent's king, and strategic positioning.

## Usage:

**Generating Chess Positions:**
   - Use the `generateRandomPosition(int numFigures)` method to generate random chess positions.
   - Specify the number of figures to include in the position, ensuring it adheres to standard chess configurations.

**Analyzing Positions:**
   - Utilize various methods within the `ChessBoard` class to analyze the generated positions.
   - Assess threats to kings, potential captures, and strategic opportunities within the position.

**Identifying Best Moves:**
   - Employ the `findAndMakesMoves(int numOfMoves)` method to identify and make the best moves within each position.
   - Specify the number of moves to consider when identifying the best moves.
   - The program will output the identified moves and their significance within the position.

## Getting Started:

To use this project, follow these steps:

**Download the Code:**
   - Clone or download the provided code files from the repository.

**Include in Your Project:**
   - Integrate the `ChessBoard` class and associated methods into your project.

**Customize as Needed:**
   - Customize the code to suit your specific requirements or integrate it into your chess-related applications.

**Compile and Run:**
   - Compile the code and execute the program to generate and analyze chess positions.

## Requirements:

- C++ Compiler
- Standard C++ Library
