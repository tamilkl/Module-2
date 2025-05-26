# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

### AIM  
To write a Python program to print a downward pyramid pattern of stars using loops.

### ALGORITHM

1. Begin the program.
2. Read an integer n from the user using input() — this will determine the number of rows in the pattern.
3. Loop through rows from 0 to n - 1:
4. Print spaces at the beginning of each row using the formula: " " * rows.
5. Print stars using a nested loop — for each row, print 2 * (n - row) - 1 stars.
6. After printing spaces and stars, use print() to move to the next line.
7. Terminate the program.

### PROGRAM
```rows=int(input())
for i in range(rows,0,-1):
    for j in range(0,i):
        print("*",end=" ")
    print()
```

### OUTPUT

![image](https://github.com/user-attachments/assets/c2d55029-730a-42ae-9912-31714fde4ad2)

### RESULT
Thus the Python program to print a downward pyramid star pattern using loops was executed successfully and the output was verified.
