# Student Performance Analyzer

A Python command-line application designed to manage student records and analyze academic performance. The application stores student information and scores in a CSV file, calculates individual student averages, and provides class performance statistics.

## Features

- Add student records.
- Validate student names and scores.
- Find a specific student.
- View all student records in a formatted table.
- Calculate an individual student's average score.
- View class performance statistics.
- Store student records in a CSV file for future use.

## Technologies Used

- Python
- CSV for data storage
- Tabulate for displaying formatted tables
- Pytest for automated testing

## Requirements

- Python 3
- The external libraries listed in `requirements.txt`

## Installation

Install the required libraries:

    pip install -r requirements.txt

## Usage

Run the application:

    python project.py

Follow the menu options displayed in the terminal to manage student records and view performance statistics.

## Testing

Run the automated tests using:

    pytest project_test.py

## Data Storage

Student records are stored in a CSV file containing the following fields:

- student_name
- first_score
- second_score
- third_score

## Project Purpose

This project was developed to practise Python programming concepts, including functions, exception handling, regular expressions, file handling, CSV processing, and automated testing.
