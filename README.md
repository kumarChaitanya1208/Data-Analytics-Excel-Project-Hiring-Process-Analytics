# Hiring Process Analytics

## Project Overview

This project is a detailed data analysis of a company's hiring process, focusing on identifying key trends and providing actionable recommendations to enhance efficiency and effectiveness. The analysis was conducted using **Microsoft Excel** and includes data cleaning, statistical calculations, and data visualization.

<img width="1141" height="767" alt="image" src="https://github.com/user-attachments/assets/95a2bb26-05d7-4d21-b19b-96e4d1a257a5" />

---

## 1. Problem Statement

The HR department, hiring managers, and support staff are collecting a large amount of data during the hiring process. They need to derive valuable insights from this data to improve hiring practices and make informed decisions. The core problem is to transform raw hiring data into meaningful, actionable intelligence.

---

## 2. Project Goal

The primary goal of this project is to analyze hiring data to provide insights and recommendations that will help the HR department improve the company's hiring process. Specific areas of focus include:

* **Gender Distribution:** Analyze the gender balance among hired candidates.
* **Salary Analysis:** Determine the average salary and analyze the distribution of offered salaries.
* **Departmental Analysis:** Understand the proportion of new hires across different departments.
* **Position Tier Analysis:** Identify the distribution of employees across various position tiers.

---

## 3. Data Preparation and Methodology

### Data Collection
The dataset was collected from the hiring team in a single Microsoft Excel worksheet. The raw data contained 7 columns and 7,168 values for each column.

### Data Cleaning
* **Data Structure:** The raw data was converted into a structured Excel table using the `Control + T` shortcut to improve visualization and analysis.
* **Missing Values:** Missing values were handled as follows:
    * 15 missing values in the `Event Name` column were filled with the mode of the values.
    * 1 missing value in the `Post Name` column was filled with the mode.
    * 1 missing value in the `Offered Salary` column was filled with the average salary value.
* **Outlier Handling:** Outliers in the `Offered Salary` column were identified and removed using a box plot visualization to ensure the accuracy of statistical analysis.

 <img width="812" height="573" alt="image" src="https://github.com/user-attachments/assets/9a72185b-3868-4f2b-85a7-b382a4bfdb56" />


### Methodology
The analysis was performed using a combination of Excel functions, Pivot Tables, and data visualization techniques (bar charts, pie charts, and box plots) to answer specific questions posed by the hiring team.

---

## 4. Detailed Analysis and Findings

### **Finding 1: Gender Distribution of Hires**
* **Task:** Determine the gender distribution of hired individuals.
* **Analysis:** A Pivot Table was used to count hired employees by gender.
* **Results:**
    * Total Hires: 4,694
    * Male Hires: 2,572 ($54.79\%$)
    * Female Hires: 1,854 ($39.50\%$)
* **Insight:** The analysis reveals a notable gender imbalance, with a significantly higher percentage of male hires compared to females.

  <img width="772" height="337" alt="image" src="https://github.com/user-attachments/assets/6d33fc85-adea-4982-bfd7-0e2ce500c194" />


### **Finding 2: Average Salary and Distribution**
* **Task:** Calculate the average salary and create class intervals to understand the salary distribution.
* **Analysis:** The average salary was calculated using the Excel formula `=ROUND(AVERAGE (B2:B7165), 2)`. A frequency distribution was then created using class intervals of 10,000 currency units.
* **Results:**
    * Average Salary: 49,878.33 currency
    * **Salary Distribution:** The largest group of employees ($781$) falls into the **40,001 - 50,000** salary range.
      
<img width="742" height="456" alt="image" src="https://github.com/user-attachments/assets/b2fbb131-90a5-49d8-857e-855d0415c9b1" />


### **Finding 3: Departmental Analysis**
* **Task:** Visualize the proportion of hired employees across different departments.
* **Analysis:** A Pivot Table was used to determine the percentage of hired employees per department, which was then visualized with a pie chart.
* **Results:**
    * The **Operations Department** has the highest number of new hires, accounting for $39.26\%$ of the total.
    * The **Human Resource Department** has the lowest representation, with only $1.49\%$ of hires.
* **Insight:** This highlights the significant hiring needs in the Operations department compared to others.

 <img width="640" height="466" alt="image" src="https://github.com/user-attachments/assets/83e09ef9-5547-49fb-9cc8-2568081fa1ac" />


### **Finding 4: Position Tier Analysis**
* **Task:** Represent the distribution of positions across different tiers.
* **Analysis:** A Pivot Table was used to count employees by `Post Name`, and the results were displayed using a bar chart.
* **Results:**
    * The highest number of employees were hired for the **'C9' position (1,240 hires)**.
    * The second-highest number was for the **'C5' position (1,182 hires)**.
* **Insight:** This indicates a concentration of hiring at these specific tiers, suggesting a high demand for roles at these levels.

<img width="662" height="431" alt="image" src="https://github.com/user-attachments/assets/87c4f8fe-73c8-4fe4-992f-0e97a6392963" />

---

## 5. Recommendations & Actions

Based on the analysis, the following recommendations are proposed to improve the hiring process:

* **Address Gender Imbalance:** The analysis revealed a gender imbalance in the hiring process. The HR department should investigate the reasons for the low percentage of female hires and implement strategies to promote gender diversity in the hiring pipeline.
* **Review Salary Strategy:** The salary distribution analysis shows a concentration of hires in the 40-50 thousand range. The company should review whether this salary range is competitive and equitable across all departments and positions.
* **Allocate Resources:** The high hiring volume in the Operations department suggests that these teams should be prioritized for additional hiring resources, while the HR department's low hiring volume might indicate a need to review its staffing strategy.
* **Tier-Specific Recruitment:** The analysis showed that the most hires were for the 'C9' and 'C5' positions. Tailor recruitment strategies to attract candidates for the high-demand `C9` and `C5` tiers, as well as to review hiring needs for lower-volume tiers.

---

## 6. Conclusion & Reflection

This project successfully leveraged data analysis to provide a comprehensive overview of the company's hiring process. It identified key trends in gender distribution, salary structures, and departmental hiring, offering valuable insights that can inform future hiring strategies. The experience enhanced my proficiency in data cleaning, statistical analysis, and data visualization using **Microsoft Excel**. The insights gained will assist the HR department and hiring managers in making data-driven decisions to foster a more efficient, effective, and diverse workforce.

**Thank You**
