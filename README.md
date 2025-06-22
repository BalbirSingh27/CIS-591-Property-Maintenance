# 🏘️ Property Maintenance Trends Analysis – Phoenix, AZ

**Neighborhood Insights: Uncovering Property Maintenance Trends in Phoenix**  
*Assessing community well-being through property maintenance complaints*

---

## 📌 Project Overview

This project analyzes property maintenance complaints reported by residents of Phoenix, Arizona. The goal is to uncover insights into which council districts report the most issues, understand how complaint resolution is handled, evaluate the inspection process, and suggest ways to enhance city services and neighborhood conditions.

---

## 🎯 Objectives

- Identify council districts with the highest and lowest number of complaints
- Analyze the relationship between complaint types, resolution status, and inspection counts
- Detect outlier cases with unusually high inspection activity
- Recommend improvements based on high-performing neighborhoods

---

## 🗃️ Dataset Summary

- **Source:** City of Phoenix Neighborhood Services  
- **Original Rows:** 106,322 → **Cleaned Rows:** 16,187  
- **Fields:**
  - `CSM_CASENO`: Case Number (Unique ID)
  - `CSM_ADDRESS`: Property Address
  - `PRC_COUN_DIST`: Council District
  - `CSM_STATUS`: Complaint Status
  - `TOTAL_INSP`: Number of Inspections
  - `NOTES`: Inspector Observations

---

## 🧼 Data Cleaning Steps

- Removed unknown or invalid addresses
- Dropped null values and notes with errors
- Grouped case statuses into meaningful buckets:
  - `Closed - Resolved`
  - `Tickets or Notices Issued`
  - `In Progress or Ongoing`
  - `Referred to Other Departments`
  - `Unresolved or Exceptional Cases`

---

## 📊 Key Findings

- **Districts 4 and 8** have the **highest number of complaints**
- **Districts 2 and 6** report the **fewest issues**, suggesting efficiency or underreporting
- **Most complaints are resolved**, but formal notices and tickets lead to more inspections
- **Outliers**: Some cases required 30–43 inspections, indicating inefficiencies
- **Top complaint topics** include overgrown vegetation, parking violations, and trash accumulation

---

## 📈 Visualizations

- Complaint Distribution by Council District
- Case Status Breakdown
- Top 10 Cases with the Most Inspections
- Average Inspections per Status Type
- Outlier Detection via Box Plot
- Word Cloud from Inspection Notes

---

## 🧠 Interpretation

- There is a **clear correlation** between the number of inspections and case complexity
- High-complaint areas may reflect **socio-economic challenges**
- Certain neighborhoods demonstrate **effective resolution strategies**
- Chronic violators skew resource use; these need targeted intervention

---

## ✅ Recommendations

- Allocate more inspection resources to high-complaint zones (Districts 4 and 8)
- Launch awareness and reporting campaigns in low-complaint areas (Districts 2 and 6)
- Study outlier cases to uncover systemic inefficiencies
- Implement **preventive maintenance programs** in areas with recurring issues

---

## 🛠 Tools Used

- **Languages**: Python  
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `wordcloud`, `tabulate`  
- **Environment**: Jupyter Notebook / Google Colab  

---

## 🤝 Team Members & Roles

| Name          | Contribution                           |
|---------------|----------------------------------------|
| Nasim Ranjbari| Pseudocode, Documentation              |
| Alvin Lee     | Pseudocode Development                 |
| Sahil Walia   | Exploratory Analysis, Code             |
| Balbir Singh  | Data Analysis, Visualization           |
| Miao          | Code Development, Data Cleaning        |

Each member contributed equally – **20%** to the overall work.

---

