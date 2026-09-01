# Search Ranking Signal Analysis & Discoverability Engine

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Database](https://img.shields.io/badge/Database-DuckDB-yellow)
![Deployment](https://img.shields.io/badge/Paper-GitHub%20Pages-green)

An end-to-end Machine Learning capstone analyzing search performance data to identify high-impact ranking signals and isolate underperforming web pages for targeted optimization.

---

## 📌 Project Overview
Content strategy teams often struggle to prioritize page updates based on objective performance data. This project builds a repeatable decision-support engine using pre-click search performance indicators (impressions, average rank position, word count, and title length) to predict engagement potential and surface high-value recommendations without target leakage.

- 📄 **Deployed Research Paper:** [View Published Paper](https://abd12315.github.io/flyrank-capstone/)
- 🎯 **Primary Model:** Random Forest Regressor ($R^2 \approx 0.850$)
- 📊 **Baseline Model:** Ridge Regression ($R^2 \approx 0.748$)

---

## 🛠️ Repository Structure

```text
flyrank-capstone/
├── index.html                                 # Deployed Research Paper HTML source
├── work/
│   └── ML_CAP_01_Ranking_Signal_Analysis.ipynb  # Main analysis & ML training notebook
└── submission/
    └── paper_url.txt                          # Verification URL for capstone submission
