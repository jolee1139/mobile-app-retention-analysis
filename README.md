# 📱 Mobile App Retention & Cohort Analysis

## 🔍 Project Overview

This project analyzes user retention patterns and cohort behavior for a hypothetical mobile application. The goal is to uncover user engagement trends over time and identify actionable insights to improve retention and long-term user value.

---

## 🎯 Objectives

- Perform **cohort analysis** based on user install date.
- Calculate **Day 1, 7, and 30 retention rates**.
- Visualize retention curves and cohort heatmaps.
- Derive **insights and recommendations** to improve user retention and engagement.

---

## 🧰 Tools & Technologies

- **SQL**: Cohort table creation and retention metric calculation
- **Python**: Data preprocessing and analysis (`pandas`, `matplotlib`, `seaborn`, `datetime`)
- **Tableau Public**: Visualization of retention curves and cohort heatmap
- **Jupyter Notebook**: Exploratory data analysis and metric tracking

---

## 📁 Dataset

- **Source**: Simulated user event dataset
- **Structure**:
  - `user_id`
  - `event_date`
  - `install_date`
  - `event_type` (e.g., `app_open`, `purchase`, etc.)

*Note: Raw dataset and cleaned sample included in `/data/` folder.*

---

## 📊 Key Metrics

- **Cohort Retention Rate**: Percentage of users still active on Day 1, 7, and 30
- **Churn Rate**: Inverse of retention
- **User Lifetime Curve**: Average active days per user over time
- **Stickiness**: DAU / MAU

---

## 📈 Visualizations

| Type             | Tool       | Link / Location     |
|------------------|------------|----------------------|
| Retention Curve  | Tableau    | [View Dashboard](#) |
| Cohort Heatmap   | Tableau    | [View Heatmap](#)   |
| Retention by Segment | Python   | See notebook 📓     |

---

## 🧠 Key Insights

- Day 1 retention is **low (~22%)**, indicating onboarding may need improvement.
- Certain cohorts (e.g., Jan 2024) show **higher long-term engagement** — investigate what was different.
- Weekends show a dip in re-engagement; potential for push campaigns.
- Recommend A/B testing an improved onboarding flow.

---

## 📌 Files & Structure

```
├── data/
│   ├── raw_user_events.csv
│   └── cleaned_retention_data.csv
├── notebooks/
│   └── retention_analysis.ipynb
├── tableau/
│   └── retention_dashboard.twbx
├── sql/
│   └── cohort_analysis_queries.sql
└── README.md
```

## 📬 Contact

If you have questions or want to collaborate, feel free to reach out:

**Joey Lee**  
[LinkedIn](https://www.linkedin.com/in/joey-lee-2322b0104/) | [Email](jolee1139@gmail.com)
