# SOFTWARE-CONSTRUCTION-AND-DEVELOPMENT
# Java Lab Programs – Threading, Synchronization, Generics, and Concurrency

This repository contains multiple Java programs demonstrating core concepts of **threading, synchronization, inter-thread communication, deadlock, and generics**.

---

## 1. Two Tables Concurrently (Threading)

**Description:**  
Print two tables concurrently using Java threads:
- Table 1: Roll number (example: 42)  
- Table 2: Date of birth day (example: 5)  

**Key Concepts:**  
- `Thread` class  
- `start()` method  
- `sleep()` for visualization  

**Usage:**  
- Run the program in any Java compiler.  
- Both tables print concurrently with interleaved outputs.

---

## 2. Random Alphabets with Threading

**Description:**  
Print all alphabets from `A-Z` using a thread with fluctuating visualization:
- Uses `Math.random()` to pick letters  
- Prints horizontally  
- Uses `start()` and `sleep()`  
- Includes `stop()` for assignment demonstration  

**Key Concepts:**  
- Threading  
- Random numbers  
- Fluctuating delays  

**Usage:**  
- Run the program. Letters appear randomly and horizontally with random delay.

---

## 3. Joint Bank Account (Thread Synchronization)

**Description:**  
Simulates two account holders accessing a joint bank account concurrently:
- Total balance: 50,000  
- User A (Abdul Ahad) withdraws 45,000  
- User B withdraws 20,000  
- Uses synchronized methods to prevent race conditions  

**Key Concepts:**  
- `synchronized` keyword  
- Thread safety  
- Shared resources  

**Usage:**  
- Run the program to see the correct order of withdrawals and safe balance handling.

---

## 4. Inter-Thread Communication – Printer Job

**Description:**  
Simulates a printer with a limited number of pages:
- Print job requests 15 pages while tray initially has 10  
- Print thread waits if pages are insufficient  
- Refill thread adds pages and notifies print thread  

**Key Concepts:**  
- `wait()` and `notify()`  
- Inter-thread communication  
- Synchronization  

**Usage:**  
- Run the program to see print thread waiting and resuming after tray refill.

---

## 5. Deadlock Demonstration and Solution

**Description:**  
- Demonstrates deadlock using 3 threads and 3 locks  
- Shows how unsequenced lock acquisition leads to deadlock  
- Solves deadlock by enforcing a strict lock order  

**Key Concepts:**  
- Deadlock  
- Synchronization blocks  
- Ordered locking to prevent deadlock  

**Usage:**  
- Run the program: first part shows deadlock (program may freeze)  
- Second part runs safely without deadlock.

---

## 6. Generic Array Subtraction

**Description:**  
- Performs subtraction on consecutive elements of arrays  
- Works for `int`, `double`, and `float` arrays using a generic method  

**Example:**  
Input: intArray = [5, 7, 3, 9, 19]
Output: [-2, 4, -6, -10]


**Key Concepts:**  
- Generics in Java (`<T extends Number>`)  
- Type conversion using `doubleValue()`  
- Consecutive subtraction  

**Usage:**  
- Modify the arrays in `main()` and run to see results.

---

## Requirements

- Java SE 8 or higher  
- Any Java IDE (Eclipse, IntelliJ) or Online Java Compiler  

---

## How to Run

1. Open the `.java` file in your IDE or online compiler.  
2. Compile and run the program.  
3. Observe the outputs for each program as described above.  

---

## Author

**Khawaja Abdul Ahad**  

- Implemented multiple Java threading, synchronization, and generic programs for lab exercises.
