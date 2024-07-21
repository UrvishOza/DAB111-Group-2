# Printed Circuit Board Process Image Project
This is a Flask web application that demonstrates the use of a processed image dataset of Printed Circuit Boards (PCB). The application reads data from a CSV file, stores it in an SQLite database, and provides a simple web interface to view the data and learn about the project.
## Features
1. Home Page: Introduction to the PCB Process Image Project.
2. About Page: Information about the dataset, including the source and variable types.
3. Data Page: Display of a sample of the dataset from the SQLite database.

# Requirements
1. Python
2. Sqlite3
3. Flask
4. Pandas

# Installation
Download the requirement file and Enter below code
 `pip install -r requirements.txt`

# Project Structure
1. TestPad_PCB_XYRGB_V2.csv: The dataset file.
2. Printed_circuit.db: The SQLite database file
3. README.md: Project documentation.

# Running the Website

`import sqlite3`
`import pandas as pd`
`import csv`
`from flask import Flask, render_template_string, render_template`
`from werkzeug.serving import run_simple`

`df= pd.read_csv("TestPad_PCB_XYRGB_V2.csv")`

## Above Code is to import necessary liberary And Read dataset csv File
