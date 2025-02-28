# Student Information System with Enhanced Sorting and Searching

## Overview

This Java-based Student Information System enhances the management of student data within a small educational institution. It builds upon a basic system by implementing efficient sorting and searching algorithms, providing a streamlined experience for organizing and retrieving student information. This project was developed to demonstrate core concepts in data structures and algorithms.

## Features

### 📚 Student Management
- Stores student details including:
    - Student Number (ID)
    - Name
    - Subjects
    - Exam Dates

### 🔍 Search Functionality
- **Binary Search:** Efficiently locates a student by their unique Student Number.

### 🔢 Sorting Algorithms
- **Bubble Sort:** Arranges subjects alphabetically for each student.
- **Insertion Sort:** Sorts students alphabetically by their names.

### 🖥️ Interactive Text-Based Menu
- Provides a user-friendly interface for:
    - Viewing student lists
    - Searching for students
    - Sorting student data

### 🧪 Testing and Output Verification
- Includes test outputs at each step to ensure the correctness of the sorting and searching algorithms.

## Algorithms Implemented

### Bubble Sort (Subject Sorting)
- Used to sort the subjects of each student alphabetically.
- Compares adjacent elements and swaps them if they are in the wrong order.
- Suitable for small datasets or nearly sorted lists.

### Insertion Sort (Student Sorting)
- Used to sort students alphabetically by their names.
- Builds the final sorted array one item at a time.
- Efficient for small datasets or partially sorted lists.

### Binary Search (Student Search)
- Used to find a student by their Student Number.
- Requires the student list to be sorted by Student Number.
- Significantly faster than linear search for large datasets.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ClementRep/Sorting_and_Algorithm.git
   cd student-information-system
