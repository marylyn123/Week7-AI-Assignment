# 🔍 Bias Audit: COMPAS Recidivism Dataset using AI Fairness 360

## 📌 Project Overview

This project audits the **COMPAS Recidivism Dataset** for pOtential racial bias in risk score predictions using the [AI Fairness 360 (AIF360)](https://aif360.mybluemix.net/) toolkit developed by IBM. The analysis focuses on fairness metrics such as **false positive rates**, **disparate impact**, and **equal opportunity difference**, especially across racial groups (e.g., African-American vs. Caucasian defendants).

---

## 🧪 Objective

- **Audit** the dataset for racial bias using Python and AIF360.
- **Visualize** key fairness metrics (e.g., FPR, TPR, statistical parity).
- **Summarize** findings and suggest **remediation strategies** in a 300-word report.

---

## 🗂️ Project Structure

```bash
📁 compas-bias-audit/
├── data/
│   └── compas-scores-two-years.csv
├── notebooks/
│   └── compas_bias_analysis.ipynb
├── reports/
│   └── bias_audit_summary.pdf
├── visuals/
│   ├── fpr_disparity.png
│   └── tpr_comparison.png
├── README.md
└── requirements.txt
🧰 Tools & Libraries
Python 3.8+

AI Fairness 360

pandas, matplotlib, seaborn

Jupyter Notebook.
