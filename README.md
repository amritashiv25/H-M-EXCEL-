# H&M Dataset

## 1. Overview
The H&M Dataset is stored in Microsoft Excel (.xlsx) format and contains structured records related to [insert domain — e.g., customer transactions, product details, sales trends].
It can be used for:
- Exploratory Data Analysis (EDA)
- Business reporting
- SQL database import
- Machine learning preprocessing

## 2. File Information
- File Name: h&m.xlsx
- Format: .xlsx (Excel 2007+ format)
- Compatible Software:
  - Microsoft Excel
  - Google Sheets
  - LibreOffice Calc
  - Python (via pandas)
  - R (via readxl)

## 3. Dataset Structure
| Column Name       | Description |
|-------------------|-------------|
| Column1           | Explain column meaning |
| Column2           | Explain column meaning |
| Column3           | Explain column meaning |
| ...               | ... |

## 4. How to Open
### 4.1 Microsoft Excel
1. Double-click h&m.xlsx.
2. Use filters, conditional formatting, and pivot tables for quick insights.

### 4.2 Google Sheets
1. Open Google Sheets.
2. Click File → Import.
3. Select the h&m.xlsx file and choose your import settings.

### 4.3 Python (pandas)
```python
import pandas as pd
df = pd.read_excel("h&m.xlsx")
print(df.head())
