# Ethiopian Public Services Information Finder

## Overview
This project is a mini semantic search engine that helps users find relevant answers to questions about Ethiopian public services. It uses Pandas for data cleaning, NumPy for basic statistics, and ChromaDB for semantic search.

## Features
- Loads FAQ data from a CSV file or uses a fallback dataset.
- Cleans missing values and duplicate questions.
- Normalizes text and filters invalid entries.
- Splits FAQ text into searchable chunks.
- Calculates dataset statistics using NumPy.
- Stores text and embeddings in ChromaDB.
- Returns the top 3 semantically similar results for a query.

## Technologies
- Python
- Pandas
- NumPy
- ChromaDB
- Jupyter Notebook / Google Colab

## Installation
Clone the repository and install the dependencies:

```bash
pip install -r requirements.txt
```

## How to Run
Open `mini_semantic_search.ipynb` in Google Colab or Jupyter Notebook and run the cells in order.

## Example Queries
- How can I get a national ID?
- How do I register a business?
- Where can I report a water supply interruption?
- How can I apply for a passport?

## Project Structure
```text
Week2/
├── ethiopian-public-services-search.ipynb
├── ethiopian-public-services-search.py
├── README.md
├── requirements.txt
└── raw_dataset.csv
```

## Note
The information is for demonstration and educational purposes. Users should confirm official requirements with the relevant Ethiopian public service office or website.