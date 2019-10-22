# Queen-s-Attack-II-No-Array-Solution-Correct-
You will be given a square chess board with one queen and a number of obstacles placed on it. Determine how many squares the queen can attack.

A queen is standing on an n x n chessboard. The chess board's rows are numbered from 1 to n, going from bottom to top. Its columns are numbered from 1 to n, going from left to right. Each square is referenced by a tuple, (r,c), describing the row, r, and column, c, where the square is located.

The queen is standing at position r_q, c_q. In a single move, she can attack any square in any of the eight directions (left, right, up, down, and the four diagonals). 

Function Description

Complete the queensAttack function in the editor below. It should return an integer that describes the number of squares the queen can attack.

queensAttack has the following parameters:
- n: an integer, the number of rows and columns in the board
- k: an integer, the number of obstacles on the board
- r_q: integer, the row number of the queen's position
- c_q: integer, the column number of the queen's position
- obstacles: a two dimensional array of integers where each element is an array of 2 integers, the row and column of an obstacle

Sample Input 0

4 0
4 4
Sample Output 0

9


Sample Input 1

5 3    5 = Chess size, 3 number of obstacles 
4 3    4,3 Position of Queen
5 5    = Obstacles position
4 2    = Obstacles position
2 3    = Obstacles position

Sample Output 1

10

HackerRank: https://www.hackerrank.com/challenges/queens-attack-2/problem

Personal Note: This challenge was done in 2 stages. My first submission was correct, however it included a long list of array which prompted the "out of memory". This submission fixes this problem using only array of obstacles.
