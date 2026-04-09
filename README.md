# BGC Donor Data Consolidation & Analysis

## Project Overview
This project focuses on consolidating fragmented donor data from multiple sources into a single, unified dataset and performing donor-level analysis to better understand donation behavior and engagement.

The goal is to create a clean, reliable dataset that can support data-driven decision-making for donor outreach and retention.

---

## Objectives
- Clean and standardize donor data from multiple sources  
- Combine datasets into a single source of truth  
- Ensure data privacy through anonymization  
- Create donor-level summary metrics  
- Analyze donation patterns and donor behavior  

---

## Project Workflow
1. **Data Cleaning & Standardization**  
   Cleaned individual datasets to ensure consistent formatting across sources  

2. **Data Consolidation**  
   Combined multiple datasets into a single master dataset  

3. **Data Quality Review**  
   Assessed missing values, duplicates, and inconsistencies  

4. **Data Anonymization**  
   Removed personally identifiable information (PII) and created unique donor IDs  

5. **Donor-Level Aggregation**  
   Created a summary dataset with:
   - Total donations  
   - Number of donations  
   - First and last donation dates  

6. **Exploratory Analysis**  
   Analyzed donation trends, donor frequency, and top contributors  

---

## Key Insights
- A small number of donors contribute a larger portion of total donations  
- Most donors made only one donation, indicating low repeat engagement  
- Missing data in donation amount and date fields impacts analysis completeness  
- Data consolidation significantly improves visibility into donor behavior  

---

## Tools & Technologies
- **Python**
- **Pandas**
- **Jupyter Notebook**
- **Git & GitHub**

---

## Project Structure

BGC-Donor-Analytics/
│
├── notebooks/
│ ├── 01_source_intake_cleaning.ipynb
│ └── 02_donor_analysis.ipynb
│
├── data/
│ ├── cleaned/
│ └── outputs/
│
├── figures/
├── outputs/
└── README.md


---

## Key Deliverables
- Consolidated donor dataset  
- Anonymized dataset for safe sharing  
- Donor-level summary dataset  
- Donation analysis and insights  

---

## Future Improvements
- Improve donor matching using email, phone, or address logic  
- Handle missing data more effectively  
- Build an interactive dashboard (Streamlit or Power BI)  
- Automate the data pipeline  

---

## Business Impact
This project demonstrates how consolidating fragmented data enables organizations to:
- Better understand donor behavior  
- Identify high-value donors  
- Improve engagement and retention strategies  
- Make more informed, data-driven decisions  

---

## Author
**Tamauri Olive**  
Aspiring Data Analyst | Transitioning from Wellness to Data Science  
