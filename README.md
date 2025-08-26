🏦 Bank IFSC Project

A project to clean, validate, and store Bank IFSC data using Python (Pandas) and PostgreSQL.

⚙️ Features
Cleans raw Bank IFSC dataset in **Jupyter Notebook**
  - Fixes **NaN, `.0`, blanks**
  - Validates **unique IFSC codes** (regex-based)
  - Standardizes **state names, STD codes, and phone numbers**
- Generates a **cleaned dataset** ready for database insertion
---
🛠️ Tech Stack

 **Python** (Pandas, NumPy, Regex, OpenPyXL)
- **Jupyter Notebook**
Git/GitHub
## 🚀 How to Run

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/Bank-IFSC-Project.git
cd Bank-IFSC-Project

2. Install dependencies:
bash
Copy code
pip install pandas numpy openpyxl jupyter

3. Open and run the Jupyter Notebook:
bash
Copy code
jupyter notebook IFSC_Data_Cleaning.ipynb

4. Output:
Combined_IFSC1.xlsx – Raw combined data from multiple sheets

cleaned_bankifsc_data.csv – Final cleaned dataset

bank_master.csv – Unique bank names with IDs


