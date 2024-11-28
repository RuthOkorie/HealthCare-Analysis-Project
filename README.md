# Health Care-Analysis-Project
---

### Project Overview
The Healthcare Analysis Dashboard provides a comprehensive view of hospital metrics and patient data to drive data-informed decision-making. By visually capturing these metrics, the dashboard supports hospital administrators in optimizing operations, improving patient's outcomes, and ensuring effective resource management. This dashboard aggregates and presents data on medical condition by gender, admission type by severity, medication and medical condition, discharge trends, admission trends, medical condition by severity,  and medical condition by admission type to identify trends, key areas for improvement and allowing for proactive measures and strategic resource planning to better serve patients and staff. 

---
## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Visualisation](#visualisation)
- [Inference and Insights](#inference-and-insights)
- [Recommendations](#recommendations)

---
### Data Sources

The primary source of data used here is Healthcare Data.csv and this is an open source data that can be freely downloaded from an open source online such as kaggle. [Download here](http://www.kaggle.com).

---

### Tools Used
---

- Microsoft Excel [Download Here](http://www.microsoft.com)
  1. This is used for initial data cleaning, formatting, and exploratory data analysis.
  2. It enabled me to pivot and analyze my data.
- Microsoft Power BI
  1. I leveraged Power Bi for data visualization and dashboard creation.
  2. This is used for transforming raw data into clear and insightful visuals.
- SQL
  1. This is used for querying and extracting relevant data from the the database.
  2. I employed SQL for  data manipulation.
- Google sheet     
  1. This is used to integrate multiple tools for comprehensive analysis.
  2. It is used to develop supplementary charts and graphs.
     
---     
### Data Cleaning and Preparation
---

**In the initial phase of Data cleaning and preparation, I perform the following actions**;
  1. Data loading and inspection
  2. Handling missing values
  3. Data normalization
  4. Data cleaning and formatting
  5. Data quality check.
     
---
### Exploratory Data Analysis
---

EDA involves the exploring of the Data to answer some questions about the data such as;
  - What are the average number of days patients spend at the hospital
  - What are the admission type by severity 
  - what are the medical conditions by gender
    
--- 
### Data Analysis
---

**This is where I include some basic line of codes, queries or even DAX expressions used during my analysis**. 

 - Total Number of Patients: 56,000 patients in total.
 - Average hospital Stay: This implies that on average, patients stay at the hospital for 15.5 days(or nights) from admission to discharge indicating a relatively long hospital stay.
 - Total Emergency Count: 18,000, which indicates a high volume of emergency cases and potential strain on resources.
  ```DAX SYNTAX
Conditional Column (Severity)
If Admission type equals Elective then 1
If Admission type equals Urgent   then 2
Else 3
 ``` 
---
### Visualisation
---

![Health care project 2](https://github.com/user-attachments/assets/3c96f978-4984-47d5-9553-06b9dd2de34b)

![Health Project](https://github.com/user-attachments/assets/2d696328-a3a8-4803-9311-001ee6701398)

---
### Inference and Insights
---

**This is where I provide key findings from the analysis**   

- 1.Medical Condition by Gender: This visual categorizes medical conditions by gender, providing valuable insights into health issues more prevalent among the male gender, such as Asthma, Cancer, Diabetes and Hypertension. 

- 2.Admission Type by Severity: Here, admission types are segmented by severity, where Elective admission equals 1, Urgent admission equals 2 and Emergency admission equals 3. From the analysis, the Elective admission type happens to be the most severe of all the admission types with a total number of 18.7 thousand patients recorded.

- 3.Medication and medical condition:
This chart shows the relationship between medications prescribed and their associated medical conditions. Aspirin appears to be the most commonly used medication for the treatment of various medical conditions.

- 4.Discharge trends:
The Discharge Trends visual highlights patient discharge patterns over time. This metric indicates year 2020 as the highest discharge trend with 11.3 thousand discharge records.

- 5.Admission Trends:
This visual captures admission trends, allowing the identification of high-traffic periods and hospital's admissions peak. From my observation, year 2020 has the highest admission rate with records of 11,307 Patients intake.

- 6.Medical Condition by Severity:
This visual breaks down medical conditions by their severity levels. From my analysis, the medical condition that is more prevalent in patients is Arthritis, making it the top on the list. About 9,308 patients suffer from this medical condition.

- 7.Medical Condition by Admission Type:
This visual groups medical conditions by admission types (such as, emergency, elective, urgent), which helps in highlighting Elective as the admission type with the highest number of medical conditions. 

- 8. Admission Type Trends by Month:
The Admission Type Trends by Month visual shows how each admission type varies across different months. It provides valuable insights into the cyclical nature of hospital admissions while highlighting the various admission types, their number of intakes and the months it occurred, making 'August' the month with the highest total admission at 4.81 thousand.

---
### Recommendations
---

- Optimize Staffing and Resource Allocation: Use insights from admission, discharge, and emergency trends to adjust staffing levels and allocate resources during peak times. For example, anticipated increases in emergency cases or seasonal patient influxes should prompt pre-emptive adjustments in staffing, bed availability, and medical supplies.

- Focus on High-Severity Cases and Preventive Measures: Identifying trends in severe medical conditions allows the hospital to prioritize resources for critical cases while also developing preventive care programs targeting prevalent, high-severity conditions. This dual approach can help reduce emergency admissions over time.

- Implement Gender-Specific and Condition-Based Care Plans: Tailor healthcare programs and preventive measures for specific gender groups and high-frequency conditions. This targeted approach not only improves patient care but can also reduce repeat hospital visits, freeing up resources for new patients.

- Enhance Inventory Management for Medications: By tracking medication usage trends associated with specific conditions, the hospital can optimize its inventory, reducing shortages and ensuring critical medications are available when needed.

- Regularly Monitor and Adjust to Emerging Trends: Admission and discharge trends, along with severity analysis, should be monitored regularly to adjust hospital operations dynamically. Monthly and seasonal variations in patient inflow provide a foundation for agile decision-making, ensuring the hospital maintains quality care standards consistently.





