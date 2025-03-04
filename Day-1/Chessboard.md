# Problem Statement

![image](https://github.com/user-attachments/assets/c43d60c0-bbe8-4e95-803f-7ecd5ef1e951)

Above is the standard representation of a chessboard.

This could be imagined as a 2D cartesian plane, with the x axis being represented by the alphabets and y axis by the numbers.

Given coordinates in the form of string, print if that cell is white or black.

Input Format
First line contains a string s.

Output Format
White or Black.

Constraints
|s|=2

Sample Testcase 0
Testcase Input
b2
Testcase Output
Black
Explanation
Self explanatory.
Sample Testcase 1
Testcase Input
a1
Testcase Output
Black
Explanation
We can clearly see a1 is black in the diagram.

## Code

def chessboard(x):

  if (x[0] in 'aceg' and x[1] in '1357') or (x[0] in 'bdfh' and x[1] in '2468'):
  
    return 'Black'
    
  else:
  
    return 'White'
    
x=input()

print(chessboard(x))
