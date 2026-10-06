# 🧹 Customer Call List - Data Cleaning & Preparation Project

## 📌 Project Overview
This project focuses on cleaning, standardizing, and preparing a messy customer contact dataset using **Python** and **Pandas**. The goal was to transform raw, unformatted data into a structured and ready-to-use **Call List** for sales or operations teams.

---

## 🛠️ Key Data Cleaning Steps Applied
1. **Removing Duplicates & Irrelevant Columns:** Eliminated duplicate records and removed extra unnecessary columns.
2. **Text Normalization:** Cleaned up whitespace, special characters, and forward slashes from `First_Name` and `Last_Name`.
3. **Phone Number Formatting:** Standardized all phone numbers into a clean `XXX-XXX-XXXX` format and removed invalid entries.
4. **Standardizing Categorical Data:** Converted variations (`Y`, `Yes`, `N`, `No`, `N/a`) in `Paying Customer` and `Do_Not_Contact` columns to uniform `Yes` / `No` values.
5. **Business Rule Filtering:** Excluded customers who requested **Do Not Contact (`Yes`)** or lacked a valid phone number.
6. **Address Splitting:** Parsed the raw address strings into separate `Street`, `State`, and `Zip_Code` columns.

---

## 📊 Before & After Comparison

### ❌ Before Cleaning (Raw Data)
<img width="1322" height="582" alt="b_fore_cleaning_call_customer_list" src="https://github.com/user-attachments/assets/abb00280-4536-4edc-b9cb-743a1cf47a51" />


### ✅ After Cleaning (Final Call List)
<img width="1152" height="415" alt="after_cleaning_call_list" src="https://github.com/user-attachments/assets/21a70780-12d4-4630-b45f-d2ac4bbf2dba" />

---
## Code SnapShots
<img width="1822" height="827" alt="code_data_cleaning_01" src="https://github.com/user-attachments/assets/31f4a903-9483-4799-a1fc-9a6322c6b947" />
<img width="1837" height="452" alt="code_data_cleaning_02" src="https://github.com/user-attachments/assets/4d88d8ec-72a8-4d82-ad51-46e4f419f438" />
<img width="1742" height="436" alt="code_data_cleaning_04" src="https://github.com/user-attachments/assets/f2463198-b334-49aa-862c-bfb10493878b" />
<img width="1782" height="822" alt="code_data_cleaning_03" src="https://github.com/user-attachments/assets/0a8db34e-2ee2-45c1-86c1-f472b58d6e85" />

---

## 💻 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy
- **Environment:** Jupyter Notebook / VS Code
