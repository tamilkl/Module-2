**Exp.No:2C
BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS**

**AIM** 

To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.


**ALGORITHM**

1. Begin the program.
2. Read two numbers input1 and input2 from the user using input().
3. Convert the inputs to integers using int().
4. Define a lambda function compare that takes two arguments a and b.
5. The lambda function performs the following comparisons:
   If a > b, it returns the string: "a is greater than b".
   Else if a < b, it returns the string: "a is smaller than b".
   Else, it returns: "a is equal to b".
6. Call the compare function with input1 and input2 as arguments.
7. Print the result of the comparison.
8. Terminate the program.


**PROGRAM**

212223060265 - SMRITHI K

compare = lambda a, b: f"{a} is greater than {b}" if a > b else (f"{a} is smaller than {b}" if a < b else f"{a} is equal to {b}")
input1 = int(input())
input2 = int(input())
print(compare(input1, input2))


**OUTPUT**

![image](https://github.com/user-attachments/assets/355eee40-cf4e-4640-ab69-aa903c2d98c7)


**RESULT**

Thus the program to check the relation between two number using lambda function has been implemented and executed successfully.
