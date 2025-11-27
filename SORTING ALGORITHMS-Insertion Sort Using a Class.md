# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:

class InsertionSorter:

 def __init__(self):
 
 self.data = []

def create_list(self):

 n = int(input("Enter the number of elements: "))
 
 print("Enter the elements:")
 
 for _ in range(n):
 
 element = int(input())
 
 self.data.append(element)
 
 
 def insertion_sort(self):
 
 for i in range(1, len(self.data)):
 
 key = self.data[i]
 
 j = i - 1
 
 
 while j >= 0 and self.data[j] > key:
 
 self.data[j + 1] = self.data[j]
 
 j -= 1
 
 self.data[j + 1] = key
 
 
 def print_list(self):
 
 print("Sorted List:", self.data)
## OUTPUT:

<img width="93" height="171" alt="image" src="https://github.com/user-attachments/assets/927d78b7-8be7-4db5-a220-7ce004eb24e5" />

## RESULT:

Thus the program has been successfully executed
