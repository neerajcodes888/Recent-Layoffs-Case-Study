# 🚨 Recent Layoffs Case Study 📊

![GitHub Repo Size](https://img.shields.io/github/repo-size/neerajcodes888/Recent-Layoffs-Case-Study)
![GitHub License](https://img.shields.io/github/license/neerajcodes888/Recent-Layoffs-Case-Study)
![GitHub Last Commit](https://img.shields.io/github/last-commit/neerajcodes888/Recent-Layoffs-Case-Study)

---

## 📌 Overview

This project presents a **data-driven analysis of recent layoffs** across industries using structured datasets and visual insights. The goal is to explore patterns, trends, and correlations in workforce reductions to inform stakeholders, analysts, and decision-makers about how layoffs evolved over time.  

The repository includes:  
- `layoffs.csv` – structured layoff dataset  
- `study.sql` – SQL queries for exploration & aggregation  
- `study.ipynb` – Jupyter Notebook with full analysis & visualizations  

---

## 🗂 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `layoffs.csv` | Dataset with metadata (date, company, industry, region, roles affected). |
| `study.sql` | SQL queries for data aggregation & insights. |
| `study.ipynb` | Jupyter Notebook for cleaning, visualization, and analysis. |
| `README.md` | This file. |
| `LICENSE` | MIT License |

---

## 🎯 Objectives

1. **Data Exploration** – Explore layoffs across industries, regions & timelines  
2. **Trend Analysis** – Identify peaks, sector hotspots & recurring patterns  
3. **Contextual Insights** – Link data trends with economic & industry events  
4. **Reporting** – Create visual & tabular insights for decision-making  

---

## 🔍 Key Insights

**1️⃣ Layoff Peaks Correspond to Economic Shifts**  
Layoffs surge during economic downturns & industry contractions. Publicly reported layoffs, e.g., in tech, show significant reductions during slowdowns.  

**2️⃣ Tech Sector Shows High Volatility**  
Major tech companies announced large layoffs. Example: *GitHub India laid off 140+ engineers* during a strategic reorganization.  
[Source](https://www.businesstoday.in/technology/news/story/tech-layoffs-github-india-fires-over-140-engineers-say-sources-375109-2023-03-28?utm_source=chatgpt.com)  

**3️⃣ Mass Layoffs Often Not Performance-Driven**  
Layoffs often happen due to restructuring or cost-cutting rather than individual performance.  

**4️⃣ Role of Sudden Economic Events**  
Startups shutting down, funding droughts, or global recessions trigger abrupt layoffs with minimal notice.  

---

## 🛠 Data & Methods

### Data Cleaning
- Standardized dates & types  
- Handled missing values  
- Normalized categorical fields (industry, region)  

### SQL Exploration (`study.sql`)
- Aggregate layoffs by year/industry/company  
- Identify top companies with maximum layoffs  

### Visualization & Statistics
- 📈 Time series of layoffs by quarter/year  
- 📊 Bar charts by sector  
- 🌍 Heatmaps for regional layoff density  

*All visualizations & analyses are in `study.ipynb`.*

---

## 🚀 How to Run

### Prerequisites
```sh
pip install pandas matplotlib seaborn sqlalchemy jupyter
