Matrix unraveling
Given an m x n matrix of characters, write a method that returns a String which
contains the concatenation of all the matrix’s diagonals, from top to bottom,
right to left.
For example, input
1 A 5 7 B N
2 B 6 8 K R
5 Q N 3 B 1

Output has to be: 1 A2 5B5 76Q B8N NK3 RB 1 as a result (with or
without spaces, doesn’t matter)


 00 (1)
 01 10 (A 2)
 02 11 20 (5 B 5)
 03 12 21 (7 6 Q)
 04 13 22
 05 14 23
 