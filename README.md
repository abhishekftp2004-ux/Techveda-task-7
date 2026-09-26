Task 7 — String Processing for Data Cleaning

## Project Overview

This project focuses on **String Processing for Data Cleaning using Python**. It demonstrates how Python string methods can be used to clean, standardize, and process text data for basic data-analysis tasks.

## Objective

Build basic text-cleaning skills needed for real-world datasets by working with common Python string operations.

## Tools & Technologies

- Python
- Jupyter Notebook
- CSV datasets

## Topics Covered

- `strip()` — remove leading and trailing spaces
- `lower()` — convert text to lowercase
- `upper()` — convert text to uppercase
- `title()` — format text in title case
- `replace()` — replace unwanted characters or text
- `split()` — divide text into parts
- `join()` — combine text parts
- Removing extra spaces
- Email text extraction
- Category standardization
- Customer data cleaning
- Employee data cleaning
- Reusable text-cleaning functions

## Project Files

| File | Description |
|---|---|
| `Task_7_String_Processing_for_Data_Cleaning.ipynb` | Complete Jupyter Notebook |
| `Task_7_String_Processing_for_Data_Cleaning.py` | Python implementation |
| `customer_dataset.csv` | Customer data for cleaning practice |
| `employee_dataset.csv` | Employee data for cleaning practice |
| `README.md` | Project documentation |

## Key Examples

### Clean a Name

```python
name = "  rahul sharma  "

clean_name = name.strip().title()

print(clean_name)
Clean an Email
email = " RAHUL@EXAMPLE.COM "

clean_email = email.strip().lower()

print(clean_email)
Clean a Category
category = "  ELECTRONICS  "

clean_category = category.strip().lower()

print(clean_category)
Remove Extra Spaces
text = "  Data   Science  "

clean_text = " ".join(text.strip().split())

print(clean_text)
Reusable Cleaning Function
def clean_record(name, email, category):
    return {
        "name": name.strip().title(),
        "email": email.strip().lower(),
        "category": category.strip().lower()
    }

record = clean_record(
    "  Rahul Sharma ",
    " RAHUL@EXAMPLE.COM ",
    " ELECTRONICS "
)

print(record)
Practical Applications

String processing can be used for:

Cleaning customer records
Standardizing employee information
Preparing email data
Cleaning product categories
Removing unwanted spaces
Standardizing text before analysis
Preparing datasets for further data processing
Learning Outcomes

After completing this task, I can:

Use common Python string methods.
Remove unwanted spaces and characters.
Standardize text using case conversion.
Split and extract information from strings.
Clean names, emails, and categories.
Create reusable text-cleaning functions.
Apply string processing to simple datasets.
Top 5 Skills
Python Programming
String Manipulation
Data Cleaning
Data Standardization
Problem Solving & Data Preparation
How to Run
Open the Jupyter Notebook.
Select a Python kernel.
Run the cells from top to bottom.
Review the cleaned output.
Use the CSV datasets for additional practice.
