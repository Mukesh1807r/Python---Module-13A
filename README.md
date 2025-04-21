# Stack Implementation using Python List

##  Aim
To implement a **Stack** using Python's built-in `list` and its methods `append()` and `pop()`. The program will:
- Push (append) three items onto the stack.
- Pop all three items from the stack.
- Display the stack before and after popping.

---

##  Procedure
1. Initialize an empty list to represent the stack.
2. Use `append()` to push three elements onto the stack.
3. Display the current state of the stack.
4. Use `pop()` to remove and display each item (LIFO order).
5. Display the stack after all pop operations.

---

## 💻 Program
```python
stack = []


for i in range(3):
    item = input()
    stack.append(item)  


print("Stack before elements are popped")
print(stack)


for i in range(3):
    stack.pop()  

print("\nStack after elements are popped:")
print(stack)


```
## Output:

![image](https://github.com/user-attachments/assets/7f3daf66-f79e-401d-b065-046a23bc3b75)

## Result:
Thus, the program was successfully created and executed.
