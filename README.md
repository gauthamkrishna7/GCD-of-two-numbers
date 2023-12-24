# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Program to find the gcd of two numbers.
#Developed by: GAUTHAM KRISHNA S    
#RegisterNumber: 23012450


def gcd():
    a = int(input())
    b = int(input())
    while b!=0:
        a,b = b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
<img width="1467" alt="image" src="https://github.com/gauthamkrishna-s/GCD-of-two-numbers/assets/146015011/30a270ee-fcdc-452e-a422-3a5e787b5ffc">



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
