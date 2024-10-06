# 📚 Data Structures: Lesson 3 - Arrays

## What are Arrays?

Arrays are one of the simplest and most fundamental data structures in programming. In fact, **99.9%** of programming languages support arrays by default, making them an essential building block for many other data structures, such as stacks, heaps, and more.

### 🌟 Key Characteristics of Arrays:

- **Fixed Size**: Arrays are stored in memory using contiguous storage units. Before inserting any elements, the array must be initialized, and its size must be specified.
- **Memory Allocation**: Once initialized, the operating system reserves a fixed amount of memory space for the array. This space cannot be resized after it’s been reserved. If more elements need to be added, a new array is created to accommodate both old and new values.
- **Indexed Access**: Arrays allow random access to elements using their index. Most programming languages use **zero-based indexing** (i.e., the first element is at index `0`), although there are some exceptions.

### 📌 Important Notes on Arrays:

1. **Memory Reservation**: When an array is initialized, the compiler communicates with the operating system, which in turn speaks to the CPU. The CPU then reserves a block of memory specifically for that array. This process ensures that all elements are stored together, which makes accessing them efficient.
   
2. **Static Size**: The size of an array cannot be changed once it’s created. If additional space is required, a new array with a larger size is created, and the old values are copied over. This is why arrays are considered a **static** data structure, unlike dynamic structures like lists or vectors.

3. **Types of Arrays**:
   - **One-Dimensional Arrays**: These are linear arrays where each element is stored in a single row.
   - **Two-Dimensional Arrays**: Often visualized as a table or matrix, two-dimensional arrays have rows and columns.
   - **Three-Dimensional Arrays**: These arrays are rarely used but have specific applications, particularly in fields like machine learning.
   - **Higher Dimensional Arrays**: While less common, arrays with more than three dimensions can be encountered in certain computational fields.

### 🧠 Why Start from Index 0?

Though not universal, most modern programming languages start array indexing at **0**. This design choice is based on optimizing memory access. Starting from `0` avoids the need for subtracting `1` in pointer arithmetic, simplifying operations and reducing overhead. However, some languages historically started arrays from `1`, and certain languages still do today.

### 🔧 Operations on Arrays

Arrays are defined by the operations that can be performed on them:

- **Access**: Retrieve an element using its index.
- **Insert**: Insert a new element (requires a new array if the size exceeds the original allocation).
- **Update**: Change the value at a specific index.
- **Delete**: Remove an element (requires shifting elements or resizing the array).

It’s important to note that accessing memory directly is controlled by the operating system and the CPU. Most programming languages provide abstract methods to handle memory safely, without giving the programmer complete low-level control.

### 🔍 Code Examples

#### C++
```cpp
#include <iostream>
using namespace std;

int main() {
    int arr[5] = {1, 2, 3, 4, 5};  // Static array initialization
    cout << "First element: " << arr[0] << endl;
    return 0;
}
```
#### JavaScript
```javascript
let arr = [1, 2, 3, 4, 5];  // Static array initialization
console.log("First element:", arr[0]);
```
