# ☕ Café Sales Data Cleaning & Dashboard Project

## 📋 Project Overview  
This project focuses on **data cleaning and comparison** between **dirty** and **clean** datasets using an interactive **Excel Dashboard**.  
The goal is to identify data quality issues, clean them systematically, and visualize the results before and after cleaning.

---

## 📂 File Contents
- **Dashboard** – Visual comparison between dirty and clean data.  
- **Dirty Café Data** – The original dataset containing missing and incorrect values.  
- **Clean Café Data** – The cleaned version after applying transformations.  
- **Price per Item** – Reference sheet used to infer correct item prices.  

---

## 🧹 Data Cleaning Steps

1. **Transaction Date:**  
   - Removed blank and incorrect values.  

2. **Item Column:**  
   - Replaced values `"Error"`, `"Unknown"`, and blanks with **"Unknown Item"**.  

3. **Quantity Column:**  
   - Replaced `"Error"`, `"Unknown"`, and blanks with the **average quantity**.  

4. **Price per Item:**  
   - Replaced incorrect values with correct prices inferred using a **Pivot Table**.  

5. **Total Spent:**  
   - Calculated using:  
     ```
     Total = Quantity * Price per Item
     ```
     - Removed or corrected `"Error"`, `"Unknown"`, and blank values.  

6. **Location & Payment Method:**  
   - Replaced `"Error"`, `"Unknown"`, and blank values with **"Unknown"**.  

7. **Final Steps:**  
   - Renamed columns for better clarity.  
   - Adjusted **data types** and **converted ranges into tables**.  

---

## 🧠 Excel Tools & Functions Used
- **Pivot Table**  
- **XLOOKUP**, **VLOOKUP**  
- **AVERAGE**, **IF**, **IFERROR**, **OR**  
- **Remove Duplicates**  
- **COUNT**, **COUNTBLANK**  

---

## 📊 Dashboard Highlights
- Comparison between **Dirty vs. Clean Data**.  
- Visual insights on total spending, item performance, and payment method distribution.  
- Improved data accuracy and readability.  

---

## 👨‍💻 Created by
**Omar Hasan**  
📅 *October 2025*  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/omar-almasri375/)
