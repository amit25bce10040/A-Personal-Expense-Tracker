# Expense Tracker (Python)

A simple command-line **Expense Tracker** built using Python and the
**os** module.\
This project allows users to **add**, **view**, **filter**, and
**delete** expenses, as well as view a **monthly summary** of their
spending.

------------------------------------------------------------------------

## 📌 Features

### ✅ Add Expense

-   Add a new expense with details such as:
    -   Amount\
    -   Category (Food, Travel, Bills, etc.)\
    -   Date\
    -   Description

### 📄 View All Expenses

-   Display all saved expenses in a clean tabular format.

### 🔍 Filter Expenses

-   Filter based on:
    -   Category\
    -   Date\
    -   Amount range

### ❌ Delete Expense

-   Remove an expense entry by its unique ID.

### 📆 Monthly Summary

-   Shows:
    -   Total monthly spending\
    -   Category-wise breakdown\
    -   Highest and lowest expenses

------------------------------------------------------------------------

## 🗂️ Project Structure

    expense_tracker/
    │── expenses.txt          # Storage file for all expenses
    │── tracker.py            # Main program logic
    │── utils.py              # Helper functions
    │── README.md             # Project documentation

------------------------------------------------------------------------

## ▶️ How to Run

1.  Ensure Python is installed (Python 3.7+ recommended)
2.  Clone or download the project folder
3.  Open terminal/cmd inside the project directory
4.  Run:

```{=html}
<!-- -->
```
    python tracker.py

------------------------------------------------------------------------

## ⚙️ Modules Used

-   `os` → For file handling, checking file existence, clearing screen,
    etc.
-   Built-in modules only (no external dependencies)

------------------------------------------------------------------------

## 📝 File Storage Format

Each expense is stored as a line inside `expenses.txt`:

    DATE | AMOUNT | CATEGORY | DESCRIPTION

Example:

    2025-01-10 | 250 | Food | Lunch with friends

------------------------------------------------------------------------
