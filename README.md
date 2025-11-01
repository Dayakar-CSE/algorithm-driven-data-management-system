# Algorithm-Driven Data Management System

### Project Context
This project is a graded programming assignment I completed as part of the **Amazon Junior Software Developer Professional Certificate** program.

The goal was to move beyond theory and apply core **Data Structures and Algorithms (DSA)** and **Object-Oriented Programming (OOP)** principles to build a complete, functional application from scratch.

---

### Technical Skills I Applied
* **Language:** **Java**
* **OOP:** I designed the system with multiple classes (`Student`, `Subject`, `Exam`, `StudentInfoSystem`). I focused on using **composition** to model real-world relationships (e.g., a `Student` *has* an `Exam` schedule).
* **Data Structures:** I used **`ArrayList`** to hold the dynamic lists of students and subjects and a **`HashMap`** for efficient, O(1) key-value data lookups.
* **Algorithms:** The main requirement was to implement these algorithms from scratch, not just use a built-in library:
    * **Binary Search:** I wrote a binary search function to find a student by their ID, which runs in $O(\log n)$ time.
    * **Insertion Sort:** I used insertion sort to keep the main student list alphabetically organized.
    * **Bubble Sort:** I implemented bubble sort to organize the list of available school subjects.

---

### Features
* A full, menu-driven console application.
* **Add Student:** Creates and stores a new student object.
* **Remove Student:** Finds and removes a student using my binary search function.
* **View Students:** Displays all students, sorted alphabetically by the insertion sort.
* **View Exam Schedule:** Demonstrates the data relationships between students, subjects, and exams.

---

### My Amazon SDE Certificate Journey
This project is one of many labs and assignments I completed for this certificate. You can see my full coursework and all related projects at my main certificate repository:

[**View My Full Amazon SDE Certificate Repository**](https://github.com/Dayakar-CSE/Amazon-Junior-Software-Developer)

---

### How to Run This Project
1.  Clone the repository:
    ```sh
    git clone https://github.com/Dayakar-CSE/algorithm-driven-data-management-system.git
    ```
2.  Open the project in any Java IDE (e.g., IntelliJ, VS Code).
3.  Compile and run the `Main.java` file to start the application.
