# Google Data Analytics Capstone (Cyclistic) — August 2024

This project is part of my **Google Data Analytics Professional Certificate**.  
It analyzes Cyclistic bike-share data (sample month: **August 2024**) to identify differences between **members** and **casual riders**.

---

## 📂 Repository Structure

- `data/`
  - `August_data_cleaned.xlsx` → cleaned dataset with added columns
  - `August_data_cleaned_trimmed.xlsx` → smaller version used in Google Sheets
  - `August_analysis_link.txt` → link to Google Sheets with pivot tables
- `docs/`
  - `Capstone_Notes.txt` → process notes
  - `Capstone_Report.docx` → draft report
- `final/`
  - `Capstone_Report.pdf` → final polished report
- `scripts/`
  - `excel_formulas.txt` → Excel formulas used to clean/prepare data
- `visuals/`
  - `Number of Rides by User Type.png`
  - `Number of Rides by Day of Week (Member vs Casual).png`
  - `Bike Type Preference (Member vs Casual).png`

---

## 📊 Analysis Steps

1. **Data Cleaning (Excel)**
   - Removed invalid rows (ride length < 1 min or > 24 hrs).
   - Created new columns: `ride_length` and `day_of_week`.
   - Saved cleaned dataset.

2. **Analysis (Google Sheets)**
   - Used trimmed dataset for pivot tables and calculations.
   - Created three pivot tables:
     - Avg ride length & ride count by user type
     - Number of rides by day of week (member vs casual)
     - Bike type preference (member vs casual)
   - Exported charts as PNG.

3. **Report**
   - Findings documented in `Capstone_Report.pdf`.

---

## ✅ Key Insights
- **Members** take **shorter but more frequent** rides.  
- **Casual riders** take **longer rides**, especially on weekends.  
- **Bike type preferences** vary between the two groups.  

---

## 📌 Data Source
Cyclistic trip data is public via [Divvy Tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html).  
Only the **cleaned August 2024 dataset** is included here due to GitHub file size limits.

---

## 🛠 Tools Used
- Excel (data cleaning)
- Google Sheets (analysis, pivot tables, charts)
- GitHub (project documentation)

---

## 👩‍💻 Author
**Aysha Minha**
