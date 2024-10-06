# 📘 Lesson 2: Stack and Heap Memory

Welcome to the second lesson in the **Data Structures Course**, where we dive into two fundamental memory regions: **stack** and **heap**. These concepts are crucial for understanding how memory is managed during program execution and how data is stored in different scenarios.

## 🗂️ Memory Management: Stack vs. Heap

In computer programs, memory is divided into two major regions: the **stack** and the **heap**. Both serve distinct purposes in terms of how data is stored, accessed, and managed.

---

### 🧩 **Stack Memory**

The **stack** is a reserved section of memory used for managing:

- **Function calls**: When a function is invoked, its local variables and return address are stored on the stack.
- **Local variables**: Variables that are only accessible within a specific function or block of code.
- **Control flow**: Tracks the order in which functions and instructions are executed.

**Key Characteristics**:
- **LIFO (Last In, First Out)**: The stack behaves like a stack data structure, where the last element added is the first to be removed.
- **Fast Access**: Since the stack is small and data access is sequential, it’s faster than heap memory.
- **Fixed Size**: The stack size is limited and generally smaller than the heap. If too much data is added to the stack, it can lead to a **stack overflow**.

---

### 🏗️ **Heap Memory**

The **heap** is another section of memory used for **dynamic memory allocation**, especially when large or complex data structures need to be managed.

- **Dynamic Memory Allocation**: Memory is allocated from the heap when you need memory at runtime (e.g., for creating objects, arrays, or linked lists).
- **Manual Management**: In some programming languages (like C/C++), memory allocated on the heap needs to be manually managed (allocated and freed). In other languages (like Java or Python), a **garbage collector** automatically manages heap memory.

**Key Characteristics**:
- **Flexible Size**: The heap is larger and more flexible than the stack, making it suitable for storing large or dynamically changing data structures.
- **Slower Access**: Accessing data from the heap is slower compared to the stack because it requires more overhead for memory management.
- **Fragmentation**: Over time, the heap may become fragmented as memory is allocated and freed, potentially leading to inefficient memory use.

---

## 💡 Important Notes

1. **Stack vs. Heap**: The stack is for short-term memory storage, usually limited to function execution and local variables, while the heap is used for long-term or dynamic memory needs.
   
2. **Memory Allocation**: In most cases, the stack is automatically managed, whereas the heap requires either manual or garbage-collected management.

3. **Stack Overflow**: If too much memory is allocated on the stack (e.g., deep recursion), it can lead to a **stack overflow**. Similarly, excessive allocation on the heap without proper management can lead to **memory leaks** or **out-of-memory errors**.

4. **Use Cases**:
   - **Stack**: Local variables, function parameters, control flow.
   - **Heap**: Large data structures, dynamic memory allocation (e.g., linked lists, trees).

---

