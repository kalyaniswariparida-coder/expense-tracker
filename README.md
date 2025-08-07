# 💸 Personal Expense Tracker (CLI - Google Colab Version)

This is a simple command-line Python app that allows users to track daily expenses.  
This version is adapted for **Google Colab** and stores data in a CSV during runtime (which can be downloaded at the end).

---

## 📌 Features

- Add new expenses (amount, category, date, note)
- View all recorded expenses
- View total spent by category
- View total spent by date
- Data saved in `expenses.csv` (can be downloaded manually)

---

## 🛠️ Technologies Used

- Python 3
- Google Colab
- CSV file handling

---

## ▶️ How to Run

1. Open this project in Google Colab  
2. Run all cells  
3. Use the menu to interact (input numbers 1–5)  
4. At the end, download your CSV if needed

---

## 📁 CSV Handling Notes

- The file `expenses.csv` is created and saved **in the current Colab session**
- To download it locally at any point, run:

```python
from google.colab import files
files.download("expenses.csv")
