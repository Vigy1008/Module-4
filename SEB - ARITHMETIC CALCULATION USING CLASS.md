# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

class Saveetha:
    def setvalues():
        Saveetha.a=int(input())
        Saveetha.b=int(input())
    def add():
        return Saveetha.a+Saveetha.b
    def div():
        return Saveetha.a/Saveetha.b
Saveetha.setvalues()
while True:
    n=int(input())
    if n==1:
        print("Result: ",Saveetha.add())
    elif n==2:
        print("Result:  {:.0f}".format(Saveetha.div()))
    elif n==0:
        print("Exiting!")
        break
    else:
        print("invalid choice")

```

### OUTPUT

![image](https://github.com/user-attachments/assets/a4024acf-fb0a-4908-bb00-be0f655d10fc)

### RESULT

Thus, the python program to perform addition and division operations using a class has been executed and verified successfully.
