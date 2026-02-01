# WordPress Transaction Automator 🚀

This Python script utilizes the **Selenium** library to automate the creation of transactions in WordPress. It is designed to save time when bulk-inserting data from a CSV file.

## ✨ Features
- Automatically reads email addresses from a CSV file.
- Fills out the "New Transaction" form automatically.
- Sets the transaction status to "Completed" by default.
- Includes a manual pause for secure login (no need to store passwords in the script).

## 🛠 Requirements
- **Python 3.x**
- **Selenium** (`pip install selenium`)
- **Webdriver** (e.g., Chrome Driver matching your browser version)

## 🚀 How to Use

1. **Prepare Data:** Create a `.csv` file (e.g., `data.csv`) with email addresses in the first column.
2. **Configuration:** Open the script and update the `CONFIGURATION` section with your file path and URL:
   ```python
   CSV_FILE = 'your_data.csv'
   BASE_URL = '[https://yourwebsite.com/wp-admin/admin.php?page=new-transaction](https://yourwebsite.com/wp-admin/admin.php?page=new-transaction)'
