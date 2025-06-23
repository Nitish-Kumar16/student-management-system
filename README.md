# 🎓 Student Management System – Java

## 📌 Project Overview
The **Student Management System** is a console-based Java application that helps manage student information and their examination records. It allows the user to add student details, input subject marks, calculate grades, and view academic performance using a simple, menu-driven interface.

## ✅ Features
- Add new students with personal details
- Add marks for 5 subjects per student
- Auto-calculation of subject grades and overall grade
- View student profile by roll number
- View subject-wise and overall exam performance
- Simple and interactive text-based menu system

## 🛠️ Technologies Used
- **Language:** Java
- **Input Handling:** Scanner class
- **Data Structures:** ArrayList, HashMap
- **OOP Concepts:** Classes, Encapsulation, Composition

## 📦 Class Structure

### `Student`
- Fields: `name`, `rollNumber`, `dob`, `email`, `studentId`, `course`
- Methods: `getName()`, `getRollNumber()`, `displayDetails()`

### `Subject`
- Fields: `name`, `marks`, `grade`, `percentage`
- Methods: `calculateGradeAndPercentage()`, `displaySubjectDetails()`

### `Examination`
- Manages a list of subjects and calculates overall performance
- Methods: `addSubject()`, `displayExamResults()`

### `StudentManagementSystem`
- Main driver class with menu options and user interaction
- Stores students and their exam data

## 🔄 Application Flow
1. **Start Application** – Menu appears to manage data.
2. **Add Student** – Inputs student details.
3. **Add Exam Details** – Inputs marks and calculates grades.
4. **View Details / Results** – Fetches student or exam info.
5. **Exit** – Ends the application.

## 💻 Sample Console Output
```
Student Management System
1. Add New Student
2. Add Examination Details
3. View Student Details
4. View Examination Results
5. Exit
Enter your choice:
```

## 🚀 How to Run
```bash
javac StudentManagementSystem.java
java StudentManagementSystem
```

## 📈 Future Enhancements
- Save/load student data to/from files (JSON, CSV)
- GUI version using JavaFX or Swing
- Email and DOB format validation
- Search or sort students by name/course

---

© 2025 Student Management System – Built with Java
