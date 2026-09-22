# OOP-Cpp-Unit-I Code Book
Student Name: Parth Bhupesh Lohi 
PRN: 125UME1165
Class/Division: S.Y-C  
Course Name: Object-Oriented Programming (OOPs) Unit I  

## List of Programs
* Program 1: Basic Data Types
* Program 2: if-else Selection Statements
* Program 3: Loop and Array Processing
* Program 4: Function Creation and Reusability
* Program 5: Classes and Objects Implementation
* Program 6: Constructors and Destructors Lifecycle
* Program 7: Static Class Members and State Tracking
* Program 8: Inline Getters and Friend Functions

---

## Brief Description of Each Program

### Program 01
📊 Basic Data Types
A foundational C++ program demonstrating the declaration and display of basic primitive data types such as integers, characters, and floating-point numbers[cite: 1].

🚀 Key Features
* **Primitive Variables:** Utilizes `int` for whole numbers, `char` for single characters, and `float` for decimal values[cite: 1].
* **Console Output:** Uses standard output streams (`cout`) to display stored values[cite: 1].

📊 Sample Output
Roll No: 101
Grade: A
Fee: 12500.5

---

### Program 02
🔀 Selection with if-else
A conditional C++ program designed to evaluate a student's score and determine pass or fail status using decision-making control flow[cite: 1].

🚀 Key Features
* **Conditional Branching:** Evaluates marks against a threshold using an `if-else` statement[cite: 1].
* **Alternative Execution:** Executes the `else` block automatically when the condition evaluates to false[cite: 1].

📊 Sample Output
Pass

---

### Program 03
🔄 Loops and Arrays
A C++ program illustrating data storage using static arrays and repetitive traversal through elements via a `for` loop[cite: 1].

🚀 Key Features
* **Array Storage:** Stores multiple student marks in a fixed-size `int` array[cite: 1].
* **Indexed Traversal:** Employs a `for` loop with an index variable `i` to access and print each array element sequentially[cite: 1].

📊 Sample Output
78 82 91 67 88

---

### Program 04
⚙️ Functions and Modular Programming
A C++ program demonstrating code reusability and modular design by implementing a separate addition function with a function prototype[cite: 1].

🚀 Key Features
* **Function Prototyping:** Informs the compiler of the function signature prior to `main` execution[cite: 1].
* **Parameter Passing & Return:** Accepts arguments, performs computation, and returns the resulting sum back to the caller[cite: 1].

📊 Sample Output
Sum = 30

---

### Program 05
🏛️ Classes and Objects
An object-oriented C++ program establishing a blueprint for student details through user-defined classes and object instantiation[cite: 1].

🚀 Key Features
* **Class Blueprint:** Encapsulates member variables (`name`, `age`) and member functions (`show()`) within a class structure[cite: 1].
* **Dot Operator Access:** Instantiates an object (`s1`) and assigns data members using the member access dot operator[cite: 1].

📊 Sample Output
Amit 20

---

### Program 06
🔄 Constructors and Destructors Lifecycle
A C++ program demonstrating the automatic invocation of special member functions during an object's lifecycle creation and termination[cite: 1].

🚀 Key Features
* **Automatic Initialization:** Executes the constructor (`Demo()`) immediately upon object creation[cite: 1].
* **Resource Cleanup:** Invokes the destructor (`~Demo()`) automatically when the object goes out of scope[cite: 1].

📊 Sample Output
Constructor called
Destructor called

---

### Program 07
📈 Static Members and Shared State
A C++ program utilizing static class members to globally track and count the total number of class instances created[cite: 1].

🚀 Key Features
* **Shared Class Variable:** Declares a `static` integer variable belonging to the class rather than any single object[cite: 1].
* **Automatic Incrementing:** Increments the shared counter inside the constructor every time a new object is instantiated[cite: 1].

📊 Sample Output
3

---

### Program 08
⚡ Inline and Friend Functions
A C++ program demonstrating advanced class feature accessibility using inline optimization techniques and non-member friend functions[cite: 1].

🚀 Key Features
* **Inline Getter:** Speeds up execution efficiency for high-frequency data access using the `inline` keyword[cite: 1].
* **Friend Function Access:** Grants a non-member external function (`show`) direct access to private class variables using the `friend` specifier[cite: 1].

📊 Sample Output
50
50
