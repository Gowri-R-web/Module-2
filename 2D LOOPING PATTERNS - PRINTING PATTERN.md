# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```
# 212223060073
# Gowri Sankari R
r=int(input())
s=(2*r)-2
for i in range(r,-1,-1):
    for j in range(s,0,-1):
        print(end=" ")
    s+=1
    for j in range(i+1):
        print("*",end=" ")
    print()

```

### OUTPUT
<img width="993" height="866" alt="2D" src="https://github.com/user-attachments/assets/fae4e9c7-da8e-4d4e-87b7-187adc0a0d92" />

### RESULT
Thus, the Python program to print a triangular star pattern using loops is successfully verified.
