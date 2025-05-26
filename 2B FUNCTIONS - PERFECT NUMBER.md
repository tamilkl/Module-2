# Exp.No:2B
## FUNCTIONS - FACTORIAL

### AIM  
To write a Python program to define a function that returns factorial of a number

---

### ALGORITHM

1.Start

2.Define a function called factorial(n)

3.Inside the function:

4.If n is 0 or 1:

5.Return 1 (since 0! = 1! = 1)

6.Otherwise:

7.Initialize a variable result = 1

8.For i from 2 to n:

9.Multiply result by i → result = result * i

10.Return result

11.Call the function with a number and print the result

12.End

---

### PROGRAM
```
def factorial(num):
if num == 1 or num == 0:
return 1
else:
return num * factorial(num-1)

num=int(input())
print(f"Factorial is {factorial(num)}")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/4abc81a7-a7b9-400b-8e46-6e64e3362e49)

### RESULT
Thus,the given python program is implemented and executed sucessfully.
