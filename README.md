# 📊 Correlation Analysis – Business Analytics Task

## 🧠 Objective
This project performs **correlation analysis** to explore relationships between investment-related factors such as:

- Age
- Investment Duration
- Expected Returns
- Preferences: Mutual Funds, Equity Market, Debentures, etc.

The goal is to understand how these factors influence one another using statistical techniques and data visualization.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn
- Matplotlib
- Excel (`.xlsx`) file as dataset

---
Visual
![ChatGPT Image Jun 15, 2025, 11_32_42 PM](https://github.com/user-attachments/assets/d3137580-5652-43f0-a718-bf2ba8bcad58)

## 🔍 What the Script Does

### ✅ 1. Load Dataset
Reads data from the provided Excel sheet using `pandas`.

### ✅ 2. Clean & Convert
- Converts categorical data (`Duration`, `Expect`) into numerical values for analysis.
- Drops missing values where necessary.

### ✅ 3. Feature Selection
Selects relevant numerical columns:
```python
['age', 'Mutual_Funds', 'Equity_Market', 'Debentures', 
 'Government_Bonds', 'Fixed_Deposits', 'PPF', 'Gold', 
 'Duration_numeric', 'Expect_numeric']

📁 Project Structure
📦 Correlation-Analysis-Task
├── 📄 correlation_analysis.py     # Python script with full code
├── 📊 correlation_matrix.png      # Heatmap output image
├── 📄 README.md                   # Project documentation
└── 📁 dataset/
    └── Data_set 2 - Copy.xlsx     # Excel dataset used in the analysis



