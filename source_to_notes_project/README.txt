# Wk4 Project Practice

This project was created to demonstrate how structured research notes can be stored in a CSV file and checked automatically using Python and pandas.


## Files

- `data/sample_notes.csv` contains sample research notes.
- `outputs/checked_notes.csv` contains the checker results.
- `notebooks/Week4_Checker.ipynb` contains the notebook code.
- `src/checker_v1.py` contains the Checker v1 Python script.

## Checker v1 Rules

The checker reviews each row and checks whether:

- A claim is present.
- A source file is present.
- A page number is present.
- The page number is valid.
- An evidence snippet is present.
- All required columns are included.

Each row is assigned one of the following statuses:

- `PASS`: The row contains all required information.
- `WARNING`: The row is mostly complete but is missing supporting information.
- `ERROR`: The row is missing critical information or contains an invalid page number.

## Purpose

The purpose of this exercise is to practice organizing project files, creating structured data, using pandas, and developing basic automated checker logic.