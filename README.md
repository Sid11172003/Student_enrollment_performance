# Student Enrollment & Academic Performance System

## Overview
This project is a Student Enrollment & Academic Performance System designed to track students, subjects, enrollments, and grades. It calculates the GPA for each student and identifies top performers. The system also provides a dashboard to visualize academic performance, making it easier for teachers and administrators to monitor and support students effectively.

## Features
- Tracks students, subjects, and enrollments
- Calculates GPA for each student
- Identifies top performers
- Visual dashboard including:
  - Table of students with their grades and GPA
  - Bar chart of average GPA per student
  - Top performer card
  - Summary cards for total students, subjects, and enrollments

## Tools Used
- **Database:** MySQL (for managing student, subject, enrollment, and grades tables)
- **Dashboard/Visualization:** Power BI 
- **Data Files:** CSV exports for tables

## Database Tables
- **Students:** `student_id`, `name`, `department`
- **Subjects:** `subject_id`, `subject_name`, `department`
- **Enrollments:** `enrollment_id`, `student_id`, `subject_id`, `semester`
- **Grades:** `grade_id`, `enrollment_id`, `grade`

## How to Use
1. Import CSV files (`Students.csv`, `Subjects.csv`, `Enrollments.csv`, `Grades.csv`) into your database.
2. Connect the database to Power BI or Sourcetable AI.
3. Load data and create visualizations to see performance metrics, average GPA, and top performers.
4. Use filters to view results by department, semester, or student.

## Future Improvements
- Automatic notifications for students with low GPA
- Attendance tracking integration
- Predictive analysis to identify students needing extra help
- More interactive dashboard with additional filters
