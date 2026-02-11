# 🤖 AI Impact on Jobs 2010–2025

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A comprehensive data analysis of how Artificial Intelligence has reshaped global job markets over 15 years.**

[📊 View Dashboard](#-interactive-dashboard) · [📓 Jupyter Notebook](#-notebook) · [📈 Visualizations](#-visualizations) · [🔍 Key Findings](#-key-findings)

</div>

---

## 📌 Project Overview

This project analyzes **5,000 global job postings** spanning **2010–2025** across **44 countries** and **9 industries** to answer:

- How rapidly has AI adoption grown in job postings?
- Which industries face the highest automation risk?
- Do AI-related jobs command a salary premium?
- What AI technologies are most in demand?
- How does job displacement risk vary by AI maturity stage?

---

## 📁 Repository Structure

```
ai-impact-jobs-analysis/
│
├── 📓 AI_Impact_Jobs_Analysis.ipynb     ← Main Jupyter Notebook
├── 📊 PowerBI_Dashboard.html            ← Interactive Dashboard
├── 📄 ai_impact_jobs_2010_2025.csv      ← Dataset (5,000 records)
├── 🐍 ai_impact_analysis.py             ← Standalone Python script
├── 📋 requirements_ai.txt               ← Dependencies
│
└── visuals/
    ├── viz1_ai_adoption_trend.png
    ├── viz2_automation_risk_industry.png
    ├── viz3_salary_ai_vs_nonai.png
    ├── viz4_top_ai_keywords.png
    ├── viz5_displacement_risk_stage.png
    └── viz6_correlation_heatmap.png
```

---

## 📊 Dataset

| Feature | Description |
|---|---|
| `posting_year` | Year of job posting (2010–2025) |
| `industry` | Sector (Tech, Finance, Healthcare, etc.) |
| `job_title` | Role (Data Scientist, ML Engineer, etc.) |
| `ai_mentioned` | Whether AI was explicitly mentioned |
| `ai_keywords` | Specific AI technologies cited |
| `ai_intensity_score` | 0–1 score of AI relevance |
| `salary_usd` | Annual salary in USD |
| `automation_risk_score` | 0–1 likelihood of role automation |
| `ai_job_displacement_risk` | Low / Medium / High |
| `industry_ai_adoption_stage` | Emerging / Growing / Mature |

**5,000 rows · 22 columns · 44 countries · 9 industries · 2010–2025**

---

## 📈 Visualizations

### 1. AI Adoption Trend (2010–2025)
> AI mentions in job postings grew from ~10% in 2010 to **68.8% in 2025**, with a major inflection point in 2018 (deep learning era) and a second surge in 2022 (LLM era).

![AI Adoption Trend](visuals/viz1_ai_adoption_trend.png)

---

### 2. Automation Risk by Industry
> Agriculture, Government, and Healthcare score highest in automation risk (>0.60), while Finance and Tech have lower but still significant scores.

![Automation Risk](visuals/viz2_automation_risk_industry.png)

---

### 3. Salary Gap: AI vs Non-AI Jobs
> AI-mentioned roles consistently pay **$20K–$30K more** annually. The gap has widened since 2016 and stands at ~$27K in 2025.

![Salary Gap](visuals/viz3_salary_ai_vs_nonai.png)

---

### 4. Top AI Keywords in Job Postings
> NLP (598), Reinforcement Learning (575), Deep Learning (572), and MLOps (569) dominate. Generative AI & LLMs appear heavily post-2022.

![AI Keywords](visuals/viz4_top_ai_keywords.png)

---

### 5. Job Displacement Risk by AI Adoption Stage
> "Growing" industries have the most postings overall; "Mature" industries show a higher proportion of **High displacement risk** relative to size.

![Displacement Risk](visuals/viz5_displacement_risk_stage.png)

---

### 6. Correlation Heatmap
> AI Intensity Score has a **weak negative correlation** with automation risk — highly specialized AI roles are paradoxically safer from automation.

![Correlation Heatmap](visuals/viz6_correlation_heatmap.png)

---

## 🔍 Key Findings

| # | Finding |
|---|---|
| 🚀 | AI job postings surged from **10% → 68.8%** between 2010 and 2025 |
| 💰 | AI-skilled roles earn a **33% salary premium** ($83.8K vs $63K average) |
| ⚠️ | **Agriculture & Government** face the highest automation risk (>0.61) |
| 🧠 | **NLP, Deep Learning & MLOps** are the most demanded AI skills |
| 📉 | Roles with higher AI intensity scores show *lower* automation risk |
| 🌍 | The dataset spans 44 countries across 9 major industries |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/theabdulwasay/ai-impact-jobs-analysis.git
cd ai-impact-jobs-analysis

# Install dependencies
pip install -r requirements_ai.txt

# Run the Jupyter notebook
jupyter notebook AI_Impact_Jobs_Analysis.ipynb

# Or run the Python script directly
python ai_impact_analysis.py
```

---

## 📦 Requirements

```
pandas>=1.5.0
matplotlib>=3.6.0
seaborn>=0.12.0
numpy>=1.23.0
jupyter>=1.0.0
```

---

## 🌐 Interactive Dashboard

Open `PowerBI_Dashboard.html` in any browser for a fully interactive Power BI-style dashboard with:
- Live KPI cards
- Clickable trend charts
- Filterable bar charts
- Stacked risk distribution
- Correlation overview

No server needed — pure HTML/CSS/JavaScript.

---

## 👤 Author

<div align="center">

**Abdul Wasay**

[![GitHub](https://img.shields.io/badge/GitHub-theabdulwasay-181717?style=for-the-badge&logo=github)](https://github.com/theabdulwasay)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdul%20Wasay-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/theabdulwasay)
[![Email](https://img.shields.io/badge/Email-abdulwasaymalik757@gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:abdulwasaymalik757@gmail.com)

</div>

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE_AI.txt](LICENSE_AI.txt) file for details.

---

<div align="center">
⭐ If you found this project helpful, please star the repository!
</div>
