# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

 AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.



 ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.



 PROGRAM

n = int(input())

sum1 = 0

for i in range(1, n):

    if(n % i == 0):
    
        sum1 = sum1 + i
        
if (sum1 == n):

    print("The number is a Perfect number!")
    
else:

    print("The number is not a Perfect number!")


 OUTPUT

![image](https://github.com/user-attachments/assets/c70f8139-5724-4f8b-b439-6a90c3783a3e)


 RESULT

Thus the  Python program to check if a number is a Perfect number using the concept of functions was implemented and executed successfully.

