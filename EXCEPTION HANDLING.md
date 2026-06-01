# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To write a python code to check if the value given in age as input is negative and then  force the program to raise an exception using raise keyword.

---

### ALGORITHM

1. Read input and convert to integer.
2. Print the entered age.
3. Check if age is less than 0; if so, raise `ValueError`.
4. Calculate year of birth as `2022 - age`.
5. Print year of birth or handle `ValueError`.


---

### PROGRAM

```
Reg.No: 212223060288
Name: Tharun Kumaran G

try:
    age= int(input())
    print("Age is:")
    print(age)
    if age<0:
        raise ValueError("Input Correct age.")
    yearOfBirth= 2022-age
    print("Year of Birth is:")
    print(yearOfBirth)
except ValueError as ve:
    print(ve)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/f12c5b71-a9a7-401b-9f52-52fe2148bc03)


### RESULT

Thus, the python program to check if the value given in age as input is negative and then  force the program to raise an exception using raise keyword has been executed and verified successfully.
