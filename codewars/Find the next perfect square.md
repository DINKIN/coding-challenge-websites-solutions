You might know some pretty large perfect squares. But what about the NEXT one?

Complete the findNextSquare method that finds the next integral perfect square after the one passed as a parameter. Recall that an integral perfect square is an integer n such that sqrt(n) is also an integer.

If the parameter is itself not a perfect square, than -1 should be returned. You may assume the parameter is positive.

Examples:

findNextSquare(121) --> returns 144
findNextSquare(625) --> returns 676
findNextSquare(114) --> returns -1 since 114 is not a perfect

### My tips
0 - Import math
1 - The sqrt(number) will return a float XX.X even if the square is a integer.
2 - So, I need to take out the integer part of this float using int(sqrt(number)), and deduct from the previous float, if the result is 0.0 the number is a perfect square (integer)
