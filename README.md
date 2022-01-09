# Home Loan Qualifier CLI

This is a command-line interface application that gives the user the ability to save the qualifying loans from various banks to a CSV file so that the results can be further shared as a excel spreadsheet.

---

## Technologies

This project leverages python 3.9.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```
---

## Usage

Ensure the conda dev environment is activated.
Using CLI, please run the python file "app.py". 
When prompted "Enter a file path to a rate-sheet (.csv):" please enter ./data/daily_rate_sheet.csv
To use the Home Loan Qualifier application...etc
Please note that the list of qualifying loans will depend on user's credit history, income, loan amount, etc.

---

## Contributors

Parag Borkar

---

## License

PMB Inc.
