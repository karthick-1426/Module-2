# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No-212223060114
#Name:KARTHICK E S
#Add your Code Here

def perfectNumber(n):
    factor_sum = 0
    if n <= 1:
        print(f"{n} is not a perfect number.")
        return
    for i in range(1, n // 2 + 1):
        if n % i == 0:
            factor_sum += i
    if factor_sum == n:
        print(f"{n} is a perfect number.")
    else:
        print(f"{n} is not a perfect number.")

a=int(input())
perfectNumber(a)
```
### OUTPUT
<img width="1396" height="721" alt="{29ADDBC2-78DA-4A70-99A0-5687941A5AD5}" src="https://github.com/user-attachments/assets/19fea993-8ca2-4699-91a5-4eec7403ab59" />

<img width="1323" height="730" alt="{1B195ABB-6C8B-4B4D-8A8B-260A1544DEA8}" src="https://github.com/user-attachments/assets/a341c16f-9692-4d46-a422-d373bf18cbf2" />


### RESULT
Therefore, the output is the example to check if a number is a Perfect number using the concept of functions.
