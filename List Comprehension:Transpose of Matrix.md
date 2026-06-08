# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:

```python
n=int(input())

scl=int(input())

l=[]

for i in range(n):

x=float(input())

l.append(x)
sq_l=[item*scl for item in l]

print(l)

print(sq_l)
```
OUTPUT:
<img width="941" height="429" alt="491492870-43ef61ae-5673-42e5-aa90-80cbca9f7184" src="https://github.com/user-attachments/assets/88afa6c8-8f93-4d87-8ecb-692c6fc25438" />


RESULT:
Thus, the program has been executed and verified successfully.
