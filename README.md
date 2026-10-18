# Student Score Analyzer

## Description
A beginner Python data-processing application that
loads student scores from a CSV file, cleans invalid
records, and calculates statistics using NumPy.

## Features
- Loads student data from a CSV file
- Cleans missing and invalid values using functions
- Processes scores using NumPy
- Calculates average, highest, and lowest scores
- Calculates the student pass rate
- Runs in a Jupyter or Google Colab notebook

## Technologies
- Python
- pandas
- NumPy
- Jupyter Notebook / Google Colab

## Requirements
Install the required packages using:

python -m pip install -r requirements.txt

## How to run
1. Install the required packages.
2. Open student_score_analyzer.ipynb.
3. Make sure students.csv is in the working directory.
4. Run the notebook cells from top to bottom.

## Data cleaning rules
- Remove rows with missing student names.
- Remove missing or non-numeric scores.
- Keep scores between 0 and 100.
- A score of 50 or above counts as a pass.
