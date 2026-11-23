# Student Academic Performance Tracker

**Created by:** Miranda Acon & Natalia De Prisco  
**Course:** BTE320 — Python Programming Capstone

## Project Overview
An interactive Python application built to help students monitor and analyze their academic progress. Users can manage courses, log assignment scores, track study sessions, evaluate academic standing, and generate data-driven performance reports using Pandas and Matplotlib.

## Key Features
* **Course Management:** Add and remove courses dynamically.
* **Grade Tracking:** Record assignments by category (Exam, Quiz, Homework) and automatically calculate course averages.
* **Study Session Logging:** Track study hours, topics, and dates per course.
* **Academic Standing:** Evaluate real-time performance tiers (*Excellent*, *Good*, *Satisfactory*, *Needs Improvement*).
* **Data Analytics & Visualizations:** Generate summary DataFrames using Pandas and visual performance charts using Matplotlib.

## Python Concepts Applied
* **Object-Oriented Programming (OOP):** Custom `Course` class encapsulating course attributes and grade-calculation methods.
* **Data Structures:** Dictionaries and nested lists for fast lookup and structured storage of assignments and study sessions.
* **Control Flow & Functions:** Modular functions, `while` loops, and conditional logic powering an interactive 12-option menu.
* **Exception Handling:** `try...except` blocks and input validation to handle invalid user entries gracefully.
* **Data Analysis:** `pandas` DataFrames for aggregating grades and study metrics, paired with `matplotlib` for visualizations.

## How to Run
1. Open `Student_Academic_Performance_Tracker.ipynb` in **Google Colab**.
2. Select **Runtime > Run all** to initialize the classes and functions.
3. Follow the interactive console menu (Options **1–12**) to input courses, grades, and study sessions or generate reports.

## Team Contributions
* **Miranda Acon:** Designed the `Course` OOP architecture, course management functions, assignment tracking, grade calculations, and academic standing logic.
* **Natalia De Prisco:** Built the study-hour and session logging system, Pandas analytical reporting, and Matplotlib visualizations.
