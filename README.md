# 📊 End-to-End HR Analytics & Workforce Retention Portfolio Project

An analytical data project investigating workforce turnover dynamics using **Python, SQL, and Power BI**. This project uncovers the core drivers of employee attrition, evaluates departmental vulnerabilities, and provides data-backed recommendations to optimize talent retention and HR strategy.

---

## 🎯 Business Objectives
* **Quantify Attrition:** Measure overall organizational turnover and benchmark baseline retention rates.
* **Identify High-Risk Segments:** Pinpoint departments, job roles, and demographic tiers experiencing elevated churn.
* **Diagnose Root Causes:** Evaluate the direct impact of compensation structures, overtime requirements, age brackets, and employee satisfaction scores on departures.
* **Deliver Actionable Insights:** Translate complex workforce metrics into strategic, executive-ready recommendations.

---

## 🛠️ Tech Stack & Tools
* **Database & Querying:** MySQL (Complex aggregations, window functions, data validation)
* **Exploratory Data Analysis:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Data Modeling & Visualization:** Power BI, DAX
* **Data Processing & Validation:** Microsoft Excel

---

## 📈 Dataset Overview & Key Metrics
The analysis is built on a cleaned enterprise HR dataset comprising employee demographic, compensation, and tenure metrics.

| Metric | Value |
| :--- | :--- |
| **Total Employees** | 1,470 |
| **Total Departures** | 237 |
| **Overall Attrition Rate** | 16.12% |
| **Average Monthly Salary** | $6,503 |
| **Average Job Satisfaction** | 2.73 / 4.0 |

---

## 🔄 Project Workflow

### 1. Data Cleaning & Preparation
* Conducted rigorous data quality assessments in Python and MySQL, checking for missing values, duplicates, and anomalies.
* Built custom employee segments to prepare data for multidimensional analysis.

### 2. Exploratory Data Analysis (Python)
* Leveraged **Pandas, NumPy, Matplotlib, and Seaborn** to visualize distributions across age, salary, tenure, and department lines.
* Evaluated correlation matrices linking work-life balance, environment satisfaction, and job satisfaction to employee turnover.

### 3. Business Analysis & Querying (MySQL)
* Wrote advanced SQL queries to extract granular insights, including department- and role-specific attrition rates, compensation gaps, promotion velocity, and overtime impact.

### 4. Interactive Dashboard Development (Power BI)
* Designed a multi-page interactive dashboard featuring an Executive Summary, Attrition Deep-Dive, Workforce Demographics, and Compensation Analysis.
* Utilized custom DAX measures, dynamic filtering, drill-through capabilities, and KPI cards to deliver a seamless user experience.

---

## 💡 Key Business Insights

* **Baseline Turnover:** The organization maintains an overall attrition rate of **16.12%** across the analyzed timeframe.
* **Departmental Vulnerability:** **Research & Development** recorded the highest absolute volume of employee exits, while specific roles such as *Sales Executives* and *Laboratory Technicians* exhibited disproportionately high turnover.
* **Operational Friction (Overtime):** Employees subjected to regular overtime showed a significantly higher propensity to leave compared to their peers.
* **Demographic Trends:** Younger employees within the **18–30 age bracket** experienced the highest churn rates, indicating potential retention friction among early-career staff.
* **Compensation & Work-Life Balance:** Lower salary tiers and poor reported work-life balance scores strongly correlate with early voluntary exits.

---

## 💼 Strategic Recommendations

1. **Optimize Workload & Overtime:** Implement structural workload reviews to minimize excessive overtime, particularly in high-risk operational units.
2. **Targeted Early-Career Retention:** Establish mentorship and structured career-pathing initiatives tailored to employees aged 18–30.
3. **Compensation Benchmarking:** Conduct a comprehensive review of salary bands in lower compensation tiers to align with market competitiveness.
4. **Work-Life Balance Programs:** Expand flexibility options and wellness initiatives to address dissatisfaction drivers.
5. **Proactive Intervention:** Utilize the Power BI monitoring framework to track high-risk departments and job roles before attrition escalates.
