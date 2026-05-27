# 📊 HR Analytics Dashboard — Power BI

> An interactive **Power BI dashboard** that analyzes employee attrition, salary trends, and workforce demographics — helping HR managers make smarter, data-driven retention decisions instantly.

---

## 📌 Project Overview

Employee attrition is one of the costliest challenges for any organization — but most HR teams don't know *why* people are leaving until it's too late. This dashboard solves that by acting as your **personal HR intelligence tool**: load the dataset, open the dashboard, and get a full workforce analysis broken down by age, salary, education, job role, and tenure — all in one place.

---

## ✨ Features

- 📤 Plug-and-play with an included **HR Analytics CSV dataset**
- 🏢 Interactive **Department filters** — HR, R&D, and Sales
- 🧠 **AI-structured visual analysis** across 6 key attrition dimensions
- 📊 **ATS-style KPI cards** — Total Employees, Attrition Rate, Avg. Salary & Age
- 👥 **Attrition by Age Group** — spot which generation is leaving most
- 💰 **Attrition by Salary Band** — see the compensation-retention link
- 🎓 **Attrition by Education Field** — understand which backgrounds churn most
- 🧑‍💼 **Attrition by Job Role** — pinpoint the highest-risk positions
- ⏳ **Attrition by Tenure** — identify the critical early-exit window
- ⚧ **Attrition by Gender** — gender-level workforce distribution

---

## 🏗️ How It Works

```
Load HR_Analytics.csv into Power BI
        ↓
Power Query  →  Clean & transform raw employee data
        ↓
DAX Measures  →  Calculate KPIs (Attrition Rate, Avg Salary, Avg Age, etc.)
        ↓
Power BI Visuals  →  Build charts across all attrition dimensions
        ↓
Dashboard Returns:
  1. KPI Summary Cards
  2. Attrition by Age Group
  3. Attrition by Salary Band
  4. Attrition by Education Field
  5. Attrition by Job Role
  6. Attrition by Years at Company
  7. Attrition by Gender
        ↓
Explore with interactive department-level filters
```

---

## 📂 Project Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics.csv        # Raw employee dataset (1,470 records)
├── Dashboard .jpeg         # Dashboard UI screenshot
└── README.md               # Project documentation
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| 🖥️ Dashboard & Visualization | Power BI Desktop |
| 📄 Data Source | CSV / Excel |
| 🔢 Calculated Measures | DAX (Data Analysis Expressions) |
| 🔄 Data Transformation | Power Query Editor |

---

## 🖼️ Dashboard Preview

![HR Analytics Dashboard](Dashboard%20.jpeg)

---

## 📈 Key Metrics at a Glance

| Metric | Value |
|--------|-------|
| 👥 Total Employees | 1,470 |
| 🚪 Attrition Count | 238 |
| 📉 Attrition Rate | 16.2% |
| 🎂 Average Age | 37 years |
| 💰 Average Salary | ₹6.5K |
| 📅 Avg. Years at Company | 7.0 years |

---

## 📊 Dashboard Insights

### 👥 Attrition by Age Group
| Age Group | Attrition Count |
|-----------|-----------------|
| 18–25 | High |
| **26–35** | **116 (Highest)** |
| 36–45 | Moderate |
| 46–55 | Low |
| 55+ | Very Low |

> 📌 Early-career employees (26–35) are the most at-risk segment.

---

### 💰 Attrition by Salary Band
| Salary Band | Attrition Count |
|-------------|-----------------|
| **Below ₹5K** | **163 (Highest)** |
| ₹5K – ₹10K | Moderate |
| ₹10K – ₹15K | Low |
| Above ₹15K | Very Low |

> 📌 Compensation is a primary driver — low earners leave at a significantly higher rate.

---

### 🎓 Attrition by Education Field
| Education Field | Attrition Share |
|-----------------|-----------------|
| Life Sciences | 37% |
| Medical | 26% |
| Marketing | 15% |
| Technical Degree | 13% |
| Other | 9% |

---

### 🧑‍💼 Attrition by Job Role
| Job Role | Attrition Count |
|----------|-----------------|
| Laboratory Technician | 62 |
| Sales Executive | 58 |
| Research Scientist | 47 |
| Sales Representative | 33 |

> 📌 Lab Technicians and Sales roles face the highest churn — targeted retention programs needed.

---

### ⏳ Attrition by Tenure
- Attrition is **highest in the first 0–2 years** of employment
- Gradually decreases as tenure increases
> 📌 Onboarding experience and early engagement are critical retention levers.

---

### ⚧ Attrition by Gender
| Gender | Employee Count |
|--------|----------------|
| Male | 889 |
| Female | 591 |

---

## ▶️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/kartheek-r/HR-Analytics-Dashboard.git
cd HR-Analytics-Dashboard
```

### 2. Install Power BI Desktop
Download and install the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/) app for Windows.

### 3. Load the Dataset
- Open **Power BI Desktop**
- Go to **Home → Get Data → Text/CSV**
- Select `HR_Analytics.csv` from the cloned folder
- Click **Load**

### 4. Build or Explore the Dashboard
- Use the included `Dashboard .jpeg` as a reference layout
- Apply DAX measures to recreate KPI cards
- Add visuals for each attrition dimension (age, salary, role, tenure, education, gender)

### 5. Use the Filters
- Apply department slicers — **HR / R&D / Sales** — to explore segment-level insights

---

## 📦 Dataset Details

**File:** `HR_Analytics.csv` — 1,470 employee records

| Column | Description |
|--------|-------------|
| `Age` | Employee age |
| `Attrition` | Whether the employee left (Yes / No) |
| `Department` | Department (HR, R&D, Sales) |
| `EducationField` | Field of education background |
| `Gender` | Employee gender |
| `JobRole` | Employee's job role/title |
| `MonthlyIncome` | Monthly salary |
| `YearsAtCompany` | Total years at the organization |
| `JobSatisfaction` | Job satisfaction rating (1–4) |
| `PerformanceRating` | Annual performance score |

> 📌 Based on the IBM HR Analytics Employee Attrition dataset — a standard benchmark for HR analysis projects.

---

## 📊 Sample Output

After opening the dashboard, you get:

| Section | What You See |
|---------|--------------|
| 📊 KPI Cards | Attrition rate, headcount, avg salary, avg age |
| 👥 Age Chart | Bar chart showing attrition by age group |
| 💰 Salary Chart | Attrition distribution across salary bands |
| 🎓 Education Donut | Breakdown by education field |
| 🧑‍💼 Role Chart | Top roles by attrition count |
| ⏳ Tenure Line | Attrition trend across years at company |
| ⚧ Gender Split | Male vs female employee distribution |

---

## 💡 Use Cases

- 🏢 HR managers tracking workforce attrition trends
- 📉 Business leaders identifying high-risk departments or roles
- 🎓 Data analysts building a Power BI portfolio project
- 🔍 Anyone exploring people analytics and HR data visualization

---

## 🔮 Future Scope

- 📄 Add a **Predictive Attrition Model** using Python / ML
- 💬 Integrate **What-If parameters** for salary scenario analysis
- 📊 Employee **Performance vs Satisfaction** correlation view
- 🌐 Publish to **Power BI Service** for web/mobile access
- 📥 Export summary insights as a **PDF report**

---

## 🙌 Conclusion

This project combines **clean HR data** and **Power BI's visualization power** to create a practical dashboard that helps organizations understand exactly which employees are at risk of leaving — and why. Built to solve a real business problem with real data, this dashboard reflects a complete end-to-end data analytics workflow: from raw CSV to actionable insight.

---

## 👨‍💻 Author

**Ryalampadu Kartheek**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartheek-ryalampadu)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kartheekryalampadu@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kartheek-r)
