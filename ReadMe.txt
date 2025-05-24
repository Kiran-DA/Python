Student Records Management System
Project Setup

This project is a simple console-based application for managing student records. It allows users to add student details, display records, calculate average marks, and save records to a CSV file.
Prerequisites

    Python 3.x
    Pandas library

Installation

    Clone the repository or download the project files.

    Navigate to the project directory in your terminal.

    Install the required libraries using pip:

    bash

    pip install pandas

Build Commands

To run the application, execute the following command in your terminal:

bash

python student_records.py

Replace student_records.py with the name of your Python file if it's different.
Functionalities

The application provides the following functionalities:

    Add Student Details:
        Users can input the student's name, roll number, and marks in three subjects (Math, Science, and Social Studies).
        The application checks for invalid names (names containing numbers).

    Display Student Records:
        Users can view all the student records that have been added.

    Calculate Average Marks:
        Users can calculate and display the average marks for each student (this functionality is currently a placeholder and can be implemented).

    Save Student Records to a File:
        Users can save the student records to a CSV file named output.csv.
        If the file already exists, new records will be appended to it.

    Exit:
        Users can exit the application.

Usage

    Run the application and follow the on-screen prompts to manage student records.
    Use the menu options to navigate through the functionalities.

Notes

    Ensure that the input for student names does not contain numbers.
    The average marks calculation functionality is a placeholder and can be implemented as needed.
