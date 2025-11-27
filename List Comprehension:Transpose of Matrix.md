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

def create(r,c):

M=[]

for i in range(int(r)):

R = []

for j in range(int(c)):

x = int(input())


R.append(x)

M.append(R)

return M

r,c = input().split()

matrix =

create(int(r),int(c))

print(matrix)

T = [[r[i]for r in matrix]for i in range(len(matrix[0]))]

print(T)


## OUTPUT:

<img width="440" height="295" alt="image" src="https://github.com/user-attachments/assets/6eed986b-5c49-4ede-a05e-aeaec6bc6721" />

## RESULT:

Thus, the given program is implemented and executed successfully

