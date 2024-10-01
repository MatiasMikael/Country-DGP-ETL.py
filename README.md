# ETL Operations on Country-GDP Data

This repository contains a Python script that performs ETL (Extract, Transform, Load) operations on GDP data of countries. The data is extracted from a Wikipedia page, transformed, and then loaded into both a CSV file and an SQLite database.

## Overview

The script performs the following steps:
1. **Extract**: Retrieves GDP data from a Wikipedia page.
2. **Transform**: Converts GDP values from millions to billions and formats them appropriately.
3. **Load**: Saves the transformed data to a CSV file and an SQLite database.
4. **Log**: Records the progress of the ETL process in a log file.

## Requirements

- Python 3.x
- Required Python libraries:
  - `beautifulsoup4`
  - `requests`
  - `pandas`
  - `numpy`
  - `sqlite3` (comes with Python standard library)

You can install the required libraries using pip:

```bash
pip install beautifulsoup4 requests pandas numpy
```

## License
This project is licensed under the MIT License. Note that it is part of the IBM Data Engineer Professional Certificate program, and original materials may have their own licensing restrictions.
