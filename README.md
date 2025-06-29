# 🧠 Employee Attrition Analysis: HR Policy Insights & Recommendations

## 📌 Project Overview

This project aims to identify which specific HR policy areas (e.g., compensation, promotion, work-life balance) are most associated with employee attrition. Using the IBM HR Analytics Employee Attrition & Performance dataset, we conducted statistical analysis and policy segmentation to propose targeted, data-driven interventions for reducing turnover risk.

> 🔍 **Problem Statement**:  
> Identify which HR policy areas are most associated with employee attrition and propose data-driven improvements to reduce turnover — especially in high-risk employee segments.

---

## 🧭 Business Objectives & Questions

**Objective:**  
Support HR policy decisions by uncovering key drivers of attrition and targeting the right employee segments for intervention.

**Key Business Questions:**
1. Which HR policies are most linked to attrition (e.g., overtime, promotion, compensation)?
2. What is the relative impact of each driver on employee turnover?
3. Which employee segments are most at risk of leaving, and why?
4. What practical, data-driven actions can improve retention among these groups?

---

## 🧪 Analytical Approach

- Exploratory Data Analysis (EDA)
- Hypothesis Testing (Chi-Square, Fisher's Exact)
- Segmented Insight Generation
- Strategy Mapping & Lifecycle Heatmaps
- Recommendations tailored by employee type

---

## 📊 Key Insights

| Driver | Key Finding |
|--------|-------------|
| **Overtime** | Employees who work overtime are nearly 3x more likely to leave. |
| **Junior Status** | Junior employees have a 2.6x higher attrition rate than others. |
| **Low Monthly Income** | Employees earning < 2,696 have 2.5x higher attrition risk. |
| **No Stock Options** | Absence of long-term incentives increases attrition, especially for married employees. |

---

## 🎯 Recommendations

| Segment | Targeted Actions |
|---------|------------------|
| **Overtime Workers** | Set overtime limits, improve time management training, rebalance workloads. |
| **Junior Employees** | Offer clearer career paths, mentoring, and more frequent reviews. |
| **Low-Income Employees** | Design structured salary progression and retention bonuses. |
| **No Stock Option Employees** | Prioritize equity for married staff; offer alternative benefits for others. |

See full strategic roadmap in [Final Solution Summary]([./final_solution_summary.pdf].

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `final_solution_summary.pdf` | Full project report with insights, logic, and recommendations |
| `EDA n Analysis.html` | Interactive HTML output of EDA and statistical analysis |
| `EDA n Analysis.Rmd` | Reproducible RMarkdown analysis code |
| `problem_define.pdf` | Business problem framing |
| `hypothesis_generation.pdf` | Hypotheses and segmentation logic |
| `final_presentation.pdf` | Slide deck summarizing project using pyramid communication |

---

## ⚠️ Limitations

- Based on a synthetic dataset (IBM HR Attrition) with no time-series or external benchmarking.
- Analysis is exploratory and explanatory; predictive modeling was not applied.
- Compensation benchmarks are internal-only.

---

## 🚀 Future Work

- Add machine learning models to predict individual attrition risk.
- Create real-time dashboards using Power BI or Tableau.
- Apply framework to other open-source HR datasets for validation.
- Package entire analysis into reusable analytics workflow (RMarkdown or Python).

---

## 📘 Acknowledgments

- Dataset Source: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Inspired by business-centered analytics frameworks and pyramid communication principles.
