# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

# AIM  
To Write a python program  to print the downward pyramid pattern of stars.

---

# ALGORITHM

1.Begin the program.

2.Input the number of rows n from the user.

3.Display the message: "Downward Pyramid Pattern:"

4.Repeat the following steps for each row i from n down to 1:
a. For each column j from 1 to i:
    - Print a * followed by a space (on the same line).
b. Move to the next line (after the inner loop ends).

5.End the program.

# PROGRAM

rows = int(input())

for i in range(rows + 1, 0, -1):

    
    for j in range(0, i - 1):

        print("*", end=' ')
        
    print(" ")

# OUTPUT

 ![image](https://github.com/user-attachments/assets/c10908e1-e936-4f46-aab4-d5ae2d56ab14)


 # RESULT

 Thus the python program  to print the downward pyramid pattern of stars was implemented and executed successfully.
