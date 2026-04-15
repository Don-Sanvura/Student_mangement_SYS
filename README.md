# Student Management System

### A File-Based Academic Record Management Application in C#

<p align="center">
  <img src="https://img.shields.io/badge/Language-C%23-blue?style=for-the-badge&logo=c-sharp">
  <img src="https://img.shields.io/badge/Framework-.NET%204.7+-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/UI-Windows%20Forms-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version%20Control-Git-black?style=for-the-badge&logo=git">
</p>

---

## Abstract

This project presents a Student Management System developed using C# and the .NET Framework. The application is designed to manage academic records through a structured file-based approach, demonstrating principles of data persistence, user interaction, and version-controlled software development.

The system integrates distributed version control using Git, leveraging the built-in capabilities of Visual Studio to synchronize local and remote repositories via GitHub. This reflects modern software engineering workflows and collaborative development practices.

---

## Introduction

Efficient management of student data is fundamental in academic environments. This application provides a simplified yet functional model of a student information system, enabling users to perform essential operations on student records through a graphical user interface.

The system emphasizes:

* Structured data storage using text files
* User-driven record management
* Integration of development tools with version control systems

---

## System Objectives

* To implement a functional student record management system
* To demonstrate CRUD operations using a file-based storage model
* To integrate Git-based version control within a development workflow
* To apply Windows Forms for user interface development

---

## Core Functionalities

* Add new student records
* Update existing student information
* View stored student records
* Delete student records
* Maintain a summary of student data

---

## Data Storage Design

The system utilizes three structured text files for persistent storage:

| File Name    | Description                                                       |
| ------------ | ----------------------------------------------------------------- |
| students.txt | Stores all student records                                        |
| summary.txt  | Stores aggregated data (average age and total number of students) |
| UserFile.txt | Stores records recently added by users                            |

This design demonstrates a lightweight alternative to database systems while maintaining logical separation of data concerns.

---

## System Workflow

```id="m9s2kp"
User Interaction → Application Logic → File Operations → Data Update → UI Display
```

The application processes user input through the interface, applies business logic, updates text-based storage, and reflects changes dynamically.

---

## Technology Stack

* C#
* .NET Framework (version 4.7 or later)
* Windows Forms
* Git and GitHub
* Visual Studio (with integrated version control tools)

---

## Installation Prerequisites

Ensure the following tools are installed:

* Visual Studio (with Git and GitHub integration enabled)
* .NET Framework 4.7 or later

---

## Setup and Execution

```bash id="zv1q1o"
git clone https://github.com/Don-Sanvura/Student_mangement_SYS.git
```

1. Open the project in Visual Studio
2. Restore any required dependencies
3. Build the solution
4. Run the application using the Visual Studio environment

---

## Version Control Integration

This project demonstrates the use of Git as a Distributed Version Control System (DVCS), including:

* Local repository management within Visual Studio
* Synchronization with a remote GitHub repository
* Tracking changes and maintaining version history

---

## Analytical Perspective

The system reflects key software engineering principles:

* File-based data persistence
* Modular program structure
* Separation between user interface and data handling
* Practical integration of development and version control tools

---

## Limitations

* Relies on text files instead of a relational database
* Limited scalability for large datasets
* Desktop-bound (no web or cloud integration)

---

## Future Enhancements

* Migration to a relational database (e.g., SQL Server)
* Implementation of authentication and role-based access
* Development of a web-based or cloud-enabled interface
* Enhanced data validation and error handling mechanisms

---

## Contribution Guidelines

Contributions are welcomed through structured pull requests. Areas of improvement include:

* Code optimization
* Feature extensions
* UI/UX enhancements
* Documentation refinement

---

## Author

Don Sanvura
Software Engineering Student

GitHub: [https://github.com/Don-Sanvura](https://github.com/Don-Sanvura)

---

## Concluding Remarks

This project provides a practical demonstration of how core software engineering concepts can be applied to build a functional data management system. It serves as a foundation for developing more advanced, scalable academic information systems aligned with enterprise-level standards.

