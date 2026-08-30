# Internship Documents - Aayush Kumar

> **Note:**  
> Some PDF files may show "Invalid PDF" or fail to preview on GitHub.  
> This is a known GitHub viewer issue.  
> Please **download** the files to view them properly. All files open correctly after downloading.

## Files Included

This repository contains the documents related to my internship:

- Internship Certificate
- Internship Report
- Internship Report PPT

---

## Internship Details

| Field                    | Details                                      |
|--------------------------|----------------------------------------------|
| **Student Name**         | AAYUSH KUMAR                                 |
| **Roll Number**          | 2410030408                                   |
| **Program**              | Bachelor of Technology (B.Tech)              |
| **Branch**               | Computer Science and Engineering             |
| **University**           | IILM University, Greater Noida               |
| **Academic Batch**       | 2024–28                                      |
| **Internship Platform**  | CodeZoner                                    |
| **Internship Domain**    | Java Data Structures and Algorithms          |
| **Project Title**        | Student Grade Management System              |

---

## Project Overview

The **Student Grade Management System** is a Java-based console application developed during the CodeZoner Virtual Internship Program.

The project was designed to manage student information and academic grades through a menu-driven interface. It allows users to:

- Add students
- View student records
- Search for students using their ID
- Sort students based on academic performance
- Update grades
- View grade details
- Generate student transcripts

The project focuses on applying Java programming concepts, data structures, algorithms, input validation, testing, logging, performance analysis, documentation, and software development practices.

---

## Project Features

- Add new students
- View all student records
- Search students by student ID
- Sort students based on percentage
- Calculate total marks, percentage, and grades
- View detailed grade information
- Update student grades
- Generate student transcripts
- Validate student marks
- Handle invalid user input
- Log system activity
- Perform unit testing using JUnit
- Perform performance testing
- Package and run the application as an executable Java JAR file

---

## Technologies and Tools Used

- Java 17
- IntelliJ IDEA
- JUnit 5
- Git & GitHub
- Java Collections Framework
- Java Logging Utilities

---

## Internship Work Summary

### Week 1 – Setup and Research
- Set up the Java development environment
- Created the GitHub repository
- Studied Java data structures and algorithms
- Created the initial `Student` class
- Implemented the basic structure of the grade management system
- Tested the application using sample student data
- Implemented grade calculation logic
- Added validation for invalid grades
- Performed basic testing

### Week 2 – Core Implementation
- Implemented student sorting functionality
- Created data structures for storing student information and grades
- Added functionality to update student grades
- Improved error handling for invalid input
- Created unit tests for grade calculation and sorting
- Performed performance testing
- Reviewed and refactored the Java code

### Week 3 – Advanced Features and Polish
- Added student transcript generation
- Optimized grade-related operations
- Conducted user testing
- Fixed reported issues
- Improved the console-based user interface
- Added logging to track system activity
- Updated project documentation

### Week 4 – Deployment and Submission
- Packaged the application as an executable Java JAR file
- Tested the packaged application
- Recorded a demonstration video of the system
- Updated the final README with usage instructions
- Submitted the project on CodeZoner
- Performed final testing and cleanup

---
## Project Structure
StudentGradeManagementSystem/
│
├── src/
│   ├── Main.java
│   │
│   ├── model/
│   │   └── Student.java
│   │
│   ├── service/
│   │   ├── StudentService.java
│   │   └── GradeCalculator.java
│   │
│   └── util/
│       ├── InputValidator.java
│       └── AppLogger.java
│
├── Test/
│   └── service/
│       ├── GradeCalculatorTest.java
│       ├── StudentServiceTest.java
│       └── StudentServicePerformanceTest.java
│
├── Internship Certificate
├── Internship Report
└── Internship Report PPT

---

## How the Application Works

The application provides a menu-driven interface with the following options:

1. Add Student  
2. View All Students  
3. Search Student  
4. Sort by Percentage  
5. View Grade Details  
6. Update Grades  
7. Generate Transcript  
8. Exit  

Users interact with the system by entering the corresponding menu option. The application validates user input and handles invalid values to prevent unexpected errors.

---

## Testing

The project was tested using:

- Manual testing
- Unit testing using JUnit
- Input validation testing
- Invalid input testing
- Performance testing
- End-to-end feature testing

The final application was also tested after packaging it as a Java JAR file.

---

## Deployment

The application was packaged as an executable Java JAR file.

Run the application using:

```bash
java -jar StudentGradeManagementSystem.jar
