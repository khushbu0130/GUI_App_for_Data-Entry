Python GUI App for Student Details
Table of Contents

Overview

Features

Requirements

Installation

Usage

Code Structure

Screenshots
 (optional)

Contributing

License

Overview

This is a simple GUI-based student details registration app built using Python and Tkinter. Data entered by the user (like name, course, semester, form number, contact number, email, and address) is saved into an Excel file (using openpyxl).

Features

Input fields for student details:

Name

Course

Semester

Form Number

Contact Number

Email ID

Address

Automatically writes submitted data into an Excel file (wb.xlsx)

Clear/reset form fields after submission

Keyboard focus control (pressing Return / Enter key moves the cursor to the next field)

Basic empty-field check to prevent writing blank entries

Requirements

Python 3.x

Tkinter (usually included with Python)

openpyxl library

pip install openpyxl

Installation

Clone or download this repository.

Make sure wb.xlsx exists in the project directory (if starting fresh, you can create an empty Excel workbook or use one provided).

Install dependencies:

pip install openpyxl


Navigate to the project folder in your terminal.

Usage

Run the main script. For example:

python app.py


(Replace app.py with the script name if different.)

Fill out the form fields:

Name

Course

Semester

Form Number

Contact Number

Email ID

Address

Press Submit to save the data into the Excel file. The form fields will then be cleared automatically.

You can also navigate through the fields using the Enter / Return key.

Code Structure

Here’s a summary of how the code is organized and how it works:

Import Modules

from tkinter import *
from openpyxl import load_workbook


Global Variables

wb – the workbook loaded from wb.xlsx

sheet – the active sheet in that workbook

Functions

focus0, focus1, … focus6 – to move keyboard focus to next field on pressing Return

clear() – clears all input fields

insert() – validates if any field is empty; if not, writes data into the next available row in the Excel sheet, then clears the form

GUI layout with Tkinter:

Labels for each field

Entry widgets for input

Grid layout used to place labels & entries

Submit Button
