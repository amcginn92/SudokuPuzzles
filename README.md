# SudokuPuzzles
This program will accept a list of sudoku puzzles and solve them. This is based off [Project Euler Problem #96](https://projecteuler.net/problem=96), so it currently has the list of 50 sudoku puzzles that it solves. For this problem we were also asked to find the sum of the 3 numbers in the top-left of each solution, which was used to verify successful completion.
This task was completed by recursively testing all possible solutions of the puzzle starting from the top-left of the board. For example, we would place '1' in the first block, and if we broke no rules in doing this, we would continue on to the next block. Once we place a number that has caused an error, we test a new number. If there are no possible solutions to that block, we know that we have no choice but to backtrack and change a number from a previous block. In this example, we might go back to our first '1' and change it to a '2'. 
There are also solutions for the Knights tour and NQueens problems. The knights tour is a problem that asks us to traverse the entire chess board using a knight and only landing on each block once. The NQueens problem is similar, but only requires us to find ways to place 8 queens so none of them can see each other as defined by the movements allowed for a queen. 
