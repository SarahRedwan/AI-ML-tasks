# Student Score Analyzer

## Description
A beginner-friendly Python data-processing application that loads student scores from a CSV file, cleans invalid records using functions, and calculates statistics using NumPy.

## Features
- Loads student data from `students.csv`
- Removes rows with missing names or scores
- Converts scores to numeric values
- Removes invalid scores and scores outside the range 0–100
- Calculates the average, highest, and lowest scores using NumPy
- Counts passing students and calculates the pass rate

## Technologies
- Python
- pandas
- NumPy
- Jupyter Notebook / Google Colab
- Git and GitHub

## Project Files
- `students.csv` — sample student dataset
- `student_score_analyzer.ipynb` — notebook containing the project code and analysis
- `requirements.txt` — required Python packages
- `.gitignore` — excludes virtual environments and temporary files

## Requirements
Install Python on your computer. Git is only needed if you want to clone or manage the repository using Git.

## Setup on Windows

### 1. Open the project folder
Open Command Prompt in the project directory.

### 2. Create a virtual environment
```bash
python -m venv .venv
```

### 3. Activate the virtual environment

For Command Prompt:
```cmd
.venv\Scripts\activate.bat
```

For PowerShell:
```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies
```bash
python -m pip install -r requirements.txt
```

### 5. Verify the packages
```bash
python -c "import pandas, numpy; print('All dependencies installed successfully!')"
```

## How to Run

### Option A: Google Colab
1. Open `student_score_analyzer.ipynb` in Google Colab.
2. Upload `students.csv` to the Colab session if it is not already available.
3. Run the notebook cells from top to bottom.

### Option B: Jupyter Notebook
1. Activate the virtual environment.
2. Install the dependencies as described above.
3. Install Jupyter if necessary:
   `python -m pip install notebook`
4. Start Jupyter:
   `python -m notebook`
5. Open `student_score_analyzer.ipynb` and run the cells from top to bottom.

## Data Cleaning Rules
- Remove records with missing student names.
- Remove records with missing or non-numeric scores.
- Keep scores between 0 and 100.
- A score of 50 or above counts as a pass.

## Example Results
Using the included sample dataset, the cleaned data should contain three students: Sara (85), Abel (90), and Mimi (70).

Expected summary:
- Total students: 3
- Average score: 81.67
- Highest score: 90
- Lowest score: 70
- Students passed: 3
- Pass rate: 100.00%

## Virtual Environment and Git
The `.venv/` directory is local to each computer and should not be committed to GitHub. The `.gitignore` file excludes `.venv/`, Python cache files, and Jupyter checkpoint files.

## Author
Student Score Analyzer — Week 1 Python data-processing project.
