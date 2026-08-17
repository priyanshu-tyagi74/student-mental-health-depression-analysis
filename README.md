# 🧠 Student Mental Health & Depression Analysis

An end-to-end data analysis project exploring how lifestyle, academic, and financial factors relate to depression among students — cleaned in **Excel** and visualized in an interactive **Tableau** dashboard.

![Dashboard Preview](![Dashboard Preview](Screenshot%202026-07-31%20000921.png))

🔗 **[View Live Interactive Dashboard on Tableau Public](https://public.tableau.com/views/StudentMentalHealthDepressionAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 📌 Project Overview

Student mental health is a growing concern, with academic pressure, financial stress, and lifestyle habits often overlooked as contributing factors. This project analyzes a survey-based dataset of ~500 students to identify patterns between **depression** and factors like age, sleep, academic pressure, financial stress, diet, and suicidal ideation.

The goal was to turn raw survey data into a clean, decision-ready dataset and a visual story that highlights actionable insights.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, formula-based transformation (Age Grouping), structuring |
| **Tableau Public** | Interactive dashboard design & data visualization |

---

## 📊 Dataset

The cleaned dataset (The cleaned dataset (`DEPRESSION CLEAN.xlsx`) contains the following fields:`) contains the following fields:

| Column | Description |
|---|---|
| Gender | Male / Female |
| Age | Age of the student |
| Age Group | Derived field — Teens / Adults |
| Academic Pressure | Self-rated pressure level (1–5) |
| Study Satisfaction | Self-rated satisfaction level (1–5) |
| Sleep Duration | Hours of sleep per night (bucketed) |
| Dietary Habits | Healthy / Moderate / Unhealthy |
| Suicidal Thoughts | Whether the student has ever had suicidal thoughts (Yes/No) |
| Study Hours | Average daily study hours |
| Financial Stress | Self-rated financial stress level (1–5) |
| Family History of Mental Illness | Yes / No |
| Depression | Target variable — Yes / No |

**Rows:** ~500 student responses

---

## 📈 Dashboard Highlights

The Tableau dashboard answers key questions such as:

- **Age Group vs Depression** — How does depression prevalence shift between teens and adults?
- **Financial Stress vs Depression** — Does higher financial stress correlate with higher depression rates?
- **Sleep Duration vs Depression** — Is there a link between sleep patterns and depression?
- **Academic Pressure vs Suicidal Thoughts** — How closely tied is academic pressure to suicidal ideation?
- **Dietary Habits vs Depression** — Do eating habits play a role in mental health outcomes?
- **Gender vs Depression** — Are there gender-based differences in reported depression?

### 🔑 Key Insights
- Students reporting **higher financial stress** show a noticeably higher share of depression cases compared to those with low financial stress.
- **Academic pressure spikes align closely with increased suicidal thoughts**, suggesting pressure management could be a key intervention point.
- Depression is **not evenly distributed across age groups** — younger students (Teens) show a different pattern compared to Adults.
- **Sleep duration** shows a visible relationship with depression, reinforcing the importance of healthy sleep habits.

---

## 📁 Repository Structure

```
student-mental-health-depression-analysis/
│
├── data/
│   └── depression_dataset.xlsx      # Cleaned dataset
│
├── images/
│   └── dashboard_preview.png        # Dashboard screenshot
│
└── README.md                        # Project documentation
```

---

## 🚀 How to Explore

1. **Live Dashboard:** Click the Tableau Public link above to interact with filters and drill into the data.
2. **Raw Data:** Download `data/depression_dataset.xlsx` to explore the cleaned dataset yourself.

---

## 👤 Author

**Priyanshu Tyagi**
📊 Data Analyst | Excel & Tableau

