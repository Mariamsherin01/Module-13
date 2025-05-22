# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```
stack = []
for i in range(1,6):
    a=input()
    stack.append(a)
x=stack[0:-2]
print(f"Stack before elements are popped \n{stack}\n\nStack after elements are popped:\n{x}")

```
### OUTPUT
---
![image](https://github.com/user-attachments/assets/b5bb109a-c6d8-4f10-b0e9-73d3de3a1d58) 
---
### RESULT 
---
Thus, The  Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`) is implemented and executed sussessfully.
---
