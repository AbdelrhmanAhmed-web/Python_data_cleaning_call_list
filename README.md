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
![Row Data](/<img width="1322" height="582" alt="b_fore_cleaning_call_customer_list" src="https://github.com/user-attachments/assets/5416a8ae-a67c-4123-a9de-195d04bd23eb" />
)

### ✅ After Cleaning (Final Call List)
![Cleaned Data](/<img width="1152" height="415" alt="after_cleaning_call_list" src="https://github.com/user-attachments/assets/10cb02d9-5563-4db5-a897-8be1d1e19a88" />
)

---

## 💻 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy
- **Environment:** Jupyter Notebook / VS Code
