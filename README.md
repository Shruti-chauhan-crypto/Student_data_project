# Student Data Analysis Project

A beginner-friendly Python project built using **Pandas** to perform data cleaning, transformation, filtering, analysis, sorting, and grouping on a student dataset.

## Features

- Load student data from a CSV file
- Inspect the dataset
- Clean missing and invalid data
- Generate Grades, Result, and Performance Score
- Filter student records
- Analyze student performance
- Sort data based on different columns
- Group data using Pandas
- Generate a final report
- Export processed data to CSV files

## Technologies Used

- Python 3
- Pandas

## Project Structure

```
Student_Data_Project/
│
├── data/
│   └── student_dataset_v2.csv
│
├── output/
│   ├── cleaned_data.csv
│   ├── toppers.csv
│   ├── failed_students.csv
│   ├── low_attendance.csv
│   ├── study_more_than_8_hours.csv
│   └── report.csv
│
├── src/
│   ├── load_data.py
│   ├── clean_data.py
│   ├── transform.py
│   ├── filter_data.py
│   ├── analyze.py
│   └── report.py
│   └── visualize.py
│
├── visualize/
│   └── attendance_distribution.png
│   └── average_marks_by_grade.png
│   └── grade_distribution.png
│   └── pass_vs_fail.png
├── main.py
└── README.md
```

## Dataset Columns

- StudentID
- Name
- StudyHours
- Attendance
- Marks
- Grades
- Result
- PerformanceScore

## Output Files

The project generates the following files inside the **output** folder:

- cleaned_data.csv
- toppers.csv
- failed_students.csv
- low_attendance.csv
- study_more_than_8_hours.csv
- report.csv

## Learning Objectives

This project helped in learning:

- Pandas DataFrames
- Data Cleaning
- Data Transformation
- Data Filtering
- Data Analysis
- Sorting
- Grouping
- CSV File Handling
- Python Functions and Project Structure

## Bonus Assessment

- Add visualization using matplotlib
- Create menu-driven application
- Display Top-10 students

## Author

**Shruti Chauhan**
