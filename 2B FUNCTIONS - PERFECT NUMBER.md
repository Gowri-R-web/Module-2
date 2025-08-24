# Exp.No:2b  
## FUNCTIONS - PALINDROME NUMBER

### AIM  
To Write a program in python to compute whether the given number is a palindrome

### ALGORITHM

1. Begin the program.
2. Read the number num from the user using input().
3. Copy the value of num into another variable called temp. 4.Set a variable rev (reverse) to 0 and Repeat the following steps while temp is greater than 0
4. Get the last digit of temp using temp % 10. Multiply rev by 10 and add the last digit to it.
5. Remove the last digit from temp using integer division (temp = temp // 10).
6. After the loop ends, compare rev with num.
7. If rev is equal to num, print "The number is a palindrome".
8. Otherwise, print "The number is not a palindrome".
9. Terminate the program.

### PROGRAM
```
# 212223060073
# Gowri Sankari R
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```
### OUTPUT
<img width="1182" height="229" alt="2B" src="https://github.com/user-attachments/assets/48934128-583a-4cbe-ae86-df3a94f80553" />


### RESULT
Thus the python program for computing whether the given number is a palindrome is executed successfully.
