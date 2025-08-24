# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
result = lambda x,y : f"The greatest number is: {x}" if x>y else (f"The greatest number is: {y}")
a=int(input())
b=int(input())
print(result(a,b))
```

### OUTPUT

<img width="1174" height="341" alt="2C" src="https://github.com/user-attachments/assets/73d3bbb6-dd1c-4b49-a27e-9e8bba1e0ad0" />


### RESULT
Thus, the Python Program for finding the greatest of two numbers using lambda function is executed sucessfully.
