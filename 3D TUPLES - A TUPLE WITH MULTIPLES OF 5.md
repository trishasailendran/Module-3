# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM


```
#Reg.no 212222060280
#Name Trisha S
l=[]
n=int(input())
for i in range(5,n,5):
    l.append(i)
t=tuple(l)
print(t)
```

### OUTPUT
<img width="786" height="228" alt="image" src="https://github.com/user-attachments/assets/a881a64d-2fdf-4b76-9add-7bd743603acc" />

### RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number N has been implemented and executed.
