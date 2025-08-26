# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
import sys
dic1 = {"A": 1, "B": 2, "C": 3} 
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print(f"Size of dic1: {sys.getsizeof(dic1)}bytes")
print(f"Size of dic2: {sys.getsizeof(dic2)}bytes")
print(f"Size of dic3: {sys.getsizeof(dic3)}bytes")
```

### OUTPUT
<img width="1175" height="308" alt="4B" src="https://github.com/user-attachments/assets/723808de-18b7-4ca0-ae9f-88a59e4ae838" />


### RESULT
Thus a Python program to print the size of a dictionary using getsizeof() from the sys module was implemented and executed successfully.
