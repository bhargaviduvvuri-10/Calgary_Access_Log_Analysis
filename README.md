# Calgary HTTP Web Server Log Analysis

This project is part of the MapUp take-home assessment and focuses on analyzing web server logs from the University of Calgary’s Computer Science department.

## 📁 Contents

- `analysis.ipynb` – Main Jupyter Notebook with data loading, cleaning, and answers to all 10 analysis questions.
- `analysis.html` – Exported version of the notebook for quick viewing.
- `transcript.txt` – Transcript of the explanation video.
- `README.md` – This file.

## 🛠 Tools Used

- Python 3
- Google Colab
- pandas
- re (regular expressions)
- datetime

## 🧹 Data Processing

- Handled Apache Common Log Format entries
- Parsed timestamps into Python `datetime` objects
- Extracted fields like method, resource, status code, and byte size
- Filtered malformed log entries

## 📊 Analysis Questions Covered

1. Total log records
2. Unique hosts
3. Unique filenames per date
4. Count of 404 responses
5. Top 404 error filenames
6. Top 404 error file extensions
7. Daily bandwidth usage (July 1995)
8. Hourly request distribution
9. Top 10 requested filenames
10. HTTP response code distribution

## 📌 Notes

- The dataset was pre-extracted from the `.gz` format.
- Malformed or incomplete lines were safely skipped.
- All questions were solved using `pandas` DataFrame operations.
- The notebook was exported with all outputs visible as required.

---

Thank you!
