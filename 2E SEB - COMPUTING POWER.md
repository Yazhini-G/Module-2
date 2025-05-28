# Exp.No:2e  
## SEB - COMPUTING NUMBER



### AIM  
To write program in python to compute whether the given number is a palindrome.



### ALGORITHM
 
1.Begin the program.

2.Input the number from the user.

3.Convert the number into a string format.

4.Compare the string representation of the number with its reverse.

If the string is equal to its reverse, then the number is a palindrome.

Otherwise, it is not a palindrome.

5.Print "The number is a palindrome" if it is a palindrome, otherwise print "The number is not a palindrome."

6.Terminate the program.


### PROGRAM

n=int(input())

rev=0

t=n

while n>0:

    r=n%10
    
    rev=rev*10+r
    
    n//=10
    
if rev==t:

    print("The given number",t,"is a Palindrome")
    
else:

    print("The given number",t,"is not a palindrome")
        

### OUTPUT
![image](https://github.com/user-attachments/assets/a59ccfa3-ee07-4249-8e1c-d14e88007575)


### RESULT

 Thus the program in python to compute whether the given number is a palindrome was implemented and executed successfully.
