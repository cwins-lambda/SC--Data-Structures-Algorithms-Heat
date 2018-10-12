Add your answers to the Algorithms exercises here.
a) This should be O(n).  Even though the while loop is n^3, inside the while loop is increasing by n^2 each time so regardless of what n is it will just run n times.

b) This looks like O(n^3).  There are three imbedded for loops that all are looping n times.  The last for loop only involves constants so does not affect the big O calculation

c) I think this is O(n) or linear time.  This will just run through the number of bunnies one at a time until it hits zero.