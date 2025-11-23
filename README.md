# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python
## 🎯 Aim:
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## 🧠 Algorithm:
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.
## 🧾 Program:
```
a=int(input())
z=bin(a)
print(z)
```
## Output:
<img width="1273" height="290" alt="image" src="https://github.com/user-attachments/assets/41a19b73-d925-4fc9-aca7-8dadaece3e35" />

## Result:
Thus, the python program was executed successfully.

# 2. Functions in Python: Modulo Calculator
## 🎯 Aim:
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## 🧠 Algorithm:
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.
## 🧾 Program:
```
def result(a,b):
    return a%b
a=int(input())
b=int(input())
print(f"modulo is {result(a,b)}")
```
## Output:
<img width="926" height="315" alt="image" src="https://github.com/user-attachments/assets/93ae10ab-8b3d-4081-afa3-958a9bb6a3d8" />

## Result:
Thus, the python program was executed successfully.

# 3. Lambda Function in Python: Addition of Two Numbers
## 🎯 Aim:
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm:
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
## 🧾 Program:
```
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```
## Output:
<img width="1234" height="367" alt="image" src="https://github.com/user-attachments/assets/7d09229d-f7d5-4a8e-a74d-7fb2e83db859" />

## Result:
Thus, the python program was executed successfully.

# 4. Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## 🎯 Aim:
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm:
Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
## 🧪 Program:
```
a=int(input())
for i in range(a):
    
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
```
## Output:
<img width="1281" height="633" alt="image" src="https://github.com/user-attachments/assets/d9373b83-8e81-47f8-b40b-ad4602d0e757" />

## Result:
Thus, the python program was executed successfully.

# 5. Loops in Python: Palindrome Number Checker
## 🎯 Aim:
To write a Python program that checks whether a given number is a palindrome using loops.

## 🧠 Algorithm:
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
## 🧾 Program:
```
num=int(input())
rev=0
temp=num

while temp>0:
    rem=temp%10
    rev=rev*10+rem
    temp//=10
    
if rev==num:
        print(f"The given number {num} is a Palindrome")
else:
        print(f"The given number {num} is not a palindrome")
```
## Output:
<img width="1229" height="323" alt="image" src="https://github.com/user-attachments/assets/053e4efa-942f-4c56-84db-d0d6cbd2db5b" />

## Result:
Thus, the python program was executed successfully.
