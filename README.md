# Crossword
This code was implemented in python. It accepts a list of words into an array list of strings, 

then makes a 20x20 matrix of characters that makes up a crossword puzzle with these words. It 

assumes that the creation of any new word other than the ones from the list is illegal.

A legal placement of a word W has the following properties:

i. All of the word W lies on the 20x20 grid;

ii. If W is not the first word, then W must intersect with one or more words on the grid;

iii. The placement of W must not create any new 'words', i.e., W cannot be adjacent to any 

letter which is not in the word(s) with which W intersects. 

This program uses various functions composed of for loops and if-else statements to verify 

whether the word is eligible to be put on the board. 

