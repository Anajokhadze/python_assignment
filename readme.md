# DE-Assessment

## Project Overview

This project is part of a data engineering assessment that involves processing and analyzing loan and claim data. The task is to process the given dataset (`data.csv`) and compute insights related to loan exposure, claims made, and the number of days since the last loan. The analysis produces an output CSV file with calculated fields.

The script performs the following key computations:
- Counts the number of claims made in the last 180 days.
- Calculates the total loan exposure excluding loans from specific banks (TBC).
- Computes the number of days since the last loan was taken.

The script processes the input CSV file (`data.csv`), and the results are saved to an output CSV file (`contract_output.csv`).

## Files

- **`data.csv`**: Input CSV file containing loan and claim data.
- **`python_assigment.pdf`**: Problem statement and assignment details.
- **`features.xlsx`**: file containing the definitions of features.
- **`main.py`**: Python script that performs data processing and calculations.
- **`contract_output.csv`**: Output CSV file containing the results of the calculations.
- **`requirements.txt`**: required libraries for running this code.



## Prerequisites

Before running the script, ensure that you have the following installed:

- **Python 3.x** (Recommended version: 3.7 or above)
- **pandas**: For reading and processing CSV files.

You can install the required libraries by using `pip` and the `requirements.txt` file.

