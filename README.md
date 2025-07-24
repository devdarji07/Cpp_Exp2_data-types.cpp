# 🧪 C++ Experiment 2: Study and Implementation of Data Types & Storage Classes

## 🎯 Aim

To:
- Understand and use data types in C++
- Explore storage classes – `auto`, `static`, `extern`, `register`
- Learn about variable scope and how many bytes are allocated to each data type

---

## 📌 Objectives

🔹 Apply different **storage classes**  
🔹 Understand the **storage**, **scope**, and **default values** of each class  
🔹 Learn how to check **memory size** using `sizeof` operator  

---

## 🧾 Program Overview

- A user-defined function demonstrates the behavior of variables under different **storage classes**.
- The `main()` function calls that user-defined function.
- The `sizeof` operator is used to determine memory usage by each data type.
  
## 🛠️ What I Used

- Storage Classes: `auto`, `extern`, `static`, `register`
- Data Types: `int`, `float`, `char`, `bool`, `short`, `long`, `double`
- `sizeof` operator to check memory size
---
## 📚 Theory: Data Types in C++

In C++, **data types** define the type and size of data that a variable can store. They are essential for memory allocation and data manipulation. C++ provides several **primitive data types** that can be used based on the requirement of the program.

### 🔹 Basic Data Types

1. **int** – Used to store integers (e.g., 1, 100, -35).  
2. **float** – Used to store floating-point numbers with decimals (e.g., 3.14, -0.55).  
3. **double** – Used for double-precision floating-point numbers; more accurate than float.  
4. **char** – Stores single characters (e.g., 'A', 'z').  
5. **bool** – Stores boolean values: `true` (1) or `false` (0).  
6. **short** – Stores smaller integers (less memory than int).  
7. **long** – Stores larger integers (more memory than int).

### 🔹 sizeof() Operator

- The `sizeof()` operator is used to determine the **memory size (in bytes)** of a data type or variable.
- It helps in understanding how much memory different types consume, which is important for optimization.

### 🔹 Memory Allocation (Typical on 64-bit systems)

| Data Type     | Memory (Bytes) | Example Value   |
|---------------|----------------|-----------------|
| `int`         | 4              | `int x = 5;`    |
| `float`       | 4              | `float f = 3.2;`|
| `double`      | 8              | `double d = 2.718;` |
| `char`        | 1              | `char c = 'A';` |
| `bool`        | 1              | `bool b = true;`|
| `short`       | 2              | `short s = 10;` |
| `long`        | 8              | `long l = 100000;` |

> ⚠️ Note: Sizes may vary depending on compiler and architecture (32-bit vs 64-bit).

### 🔹 Importance

Understanding data types is crucial for:
- Efficient memory usage
- Ensuring proper data operations
- Avoiding type mismatches and overflow errors



## 🗂️ Storage Classes Explained

### 🔸 Auto
- Default for local variables.
- Lifetime: Inside function only.
- Default value: **Garbage**

##✅ Conclusion

This experiment helped in understanding how storage classes affect the lifetime, scope, and default values of variables.  
It also strengthened the knowledge of different data types and memory usage using `sizeof`.

