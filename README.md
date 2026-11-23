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

   ## Step by Step Instruction for Success
1. **Open the Notebook:** Click on `Student_Academic_Performance_Tracker.ipynb` in this repository and open it in **Google Colab**.
2. **Start the Program:** In Google Colab, click **Runtime > Run all** in the top menu to load the classes, functions, and interactive menu.
3. **Follow the Recommended Workflow:**
   * **Step 1 — Add Your Courses:** Start by adding at least one course so the system can store your records.
   * **Step 2 — Log Your Data:** Record your assignments (Exam, Quiz, or Homework) and log your study sessions with dates and hours.
   * **Step 3 — View Analytics & Reports:** Check your academic standing, generate a Pandas summary report, or view Matplotlib graphs to see how your study hours compare to your grades.
4. **Navigate the 12 Menu Options:** Type a number from **1 to 12** when prompted and press **Enter**:
   * **Options 1–4 (Course & Grade Management):** Add courses, record assignments, view course assignments, and check academic standing.
   * **Options 5–8 (Study Session Tracking):** Log study hours, view study sessions, calculate total study time, and remove courses.
   * **Options 9–11 (Reports & Visualizations):** Generate the Pandas Academic Performance Report and display visual charts.
   * **Option 12 (Exit):** Safely close the interactive menu.

## Team Contributions
* **Miranda Acon:** Designed the `Course` OOP architecture, course management functions, assignment tracking, grade calculations, and academic standing logic.
* **Natalia De Prisco:** Built the study-hour and session logging system, Pandas analytical reporting, and Matplotlib visualizations.
