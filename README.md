# Data-Structures # Data Structures in Python 📚🐍

This repository contains notes, examples, and practice programs on **Data Structures in Python**.  
Data structures are ways of **organizing and storing data** so that they can be used efficiently.  

---

## 🚀 About the Project
- Helps beginners understand the **built-in data structures** in Python.  
- Covers **user-defined data structures** like stacks, queues, and linked lists.  
- Includes examples and practice files for hands-on learning.  

---

## 📂 Repository Structure
├── built_in/
│ ├── list_examples.py
│ ├── tuple_examples.py
│ ├── set_examples.py
│ └── dict_examples.py
│
├── user_defined/
│ ├── stack.py
│ ├── queue.py
│ ├── linked_list.py
│ └── tree.py
│
└── README.md

yaml
Copy code

---

## 📖 Topics Covered

### 🔹 Built-in Data Structures
1. **List** – Ordered, mutable collection.  
```python
fruits = ["apple", "banana", "cherry"]
fruits.append("mango")
print(fruits)   # ['apple', 'banana', 'cherry', 'mango']
Tuple – Ordered, immutable collection.

python
Copy code
numbers = (1, 2, 3)
print(numbers[0])   # 1
Set – Unordered, no duplicate elements.

python
Copy code
s = {1, 2, 2, 3}
print(s)   # {1, 2, 3}
Dictionary – Key-value pairs.

python
Copy code
student = {"name": "Alice", "age": 21}
print(student["name"])   # Alice
🔹 User-defined Data Structures
Stack (LIFO)

python
Copy code
stack = []
stack.append(1)
stack.append(2)
print(stack.pop())   # 2
Queue (FIFO)

python
Copy code
from collections import deque
queue = deque([1, 2, 3])
queue.append(4)
print(queue.popleft())   # 1
Linked List

python
Copy code
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

node1 = Node(10)
node2 = Node(20)
node1.next = node2
print(node1.next.data)   # 20
Tree (Basic Example)

python
Copy code
class TreeNode:
    def __init__(self, value):
        self.value = value
        self.left = None
        self.right = None

root = TreeNode(10)
root.left = TreeNode(5)
root.right = TreeNode(15)
print(root.left.value)   # 5
🛠️ Installation
Make sure you have Python installed (>=3.8).

Run examples like:

bash
Copy code
python built_in/list_examples.py
python user_defined/stack.py
🎯 Learning Resources
Python Official Docs – Data Structures

GeeksforGeeks – Python Data Structures

