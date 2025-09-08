
---

# 💳 Credit Card Default Prediction — Machine Learning for Financial Risk Mitigation  
> *Building & Comparing ML Models to Predict High-Risk Borrowers — With Surprising Insights on Gender, Education, and Model Performance*

![Python](https://img.shields.io/badge/Python-Scikit--learn%20+%20Pandas-blue?logo=python)  
![ML](https://img.shields.io/badge/Machine%20Learning-Decision%20Tree%20+%20Random%20Forest-orange)  
![Finance](https://img.shields.io/badge/Finance-Credit%20Risk%20+%20Default%20Prediction-green)  
![Accuracy](https://img.shields.io/badge/Accuracy-82.01%25%20(Decision%20Tree)-red)  
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20(3K%20rows%2C%2025%20features)-purple)  
![Insight](https://img.shields.io/badge/Key%20Insight-60.37%25%20of%20defaulters%20are%20female-lightgrey)

## 📊 Key Insights & Business Implications

### 1. 🎯 Model Performance: Decision Tree Wins
| Model          | Accuracy | Why Chosen                                      | Business Value                          |
|----------------|----------|-------------------------------------------------|-----------------------------------------|
| **Decision Tree** | **82.01%** | Higher accuracy + full interpretability       | Explainable AI for regulators & auditors |
| Random Forest  | 81.50%   | Ensemble robustness — but less transparent     | Good for low-stakes, high-volume use    |

> 📌 **Risk Manager’s Takeaway**: “Use Decision Tree for high-risk portfolios where model transparency is required. Use Random Forest for batch scoring of low-risk applicants.”

---

### 2. 👩‍🎓 Counterintuitive Risk Factors: Education ≠ Safety

```plaintext
Pie Chart of Defaulters by Education:
- Graduate: 46.77%
- University: 35.28%
- High School: 16.39%
- Other: 1.56%
```

> 📌 **Underwriting Insight**: “Do not assume higher education = lower risk. Our data shows graduate degree holders are the largest default cohort. Re-evaluate scoring weights.”

---

### 3. ♀️ Gender Imbalance in Default: 60.37% Female

```plaintext
Pie Chart of Defaulters by Gender:
- Female: 60.37%
- Male: 39.63%
```

> 📌 **Compliance Alert**: “This disparity requires investigation. Is it behavioral (spending patterns)? Structural (income inequality)? Or data bias? Do not use gender as a feature without fairness audits.”

---

### 4. 💳 Financial Domain Fluency: You Understand the Product

You didn’t just model — you explained:
- **What is a credit card?** Borrowed funds, interest, credit score impact.
- **Types of cards**: Rewards, Store, Secured — each with different risk profiles.
- **Approval criteria**: FICO score, income, credit history — the real-world inputs to your model.
- **Credit vs. Debit**: Borrowed money (credit) vs. your money (debit) — critical for risk context.

> 📌 **Product Manager’s Note**: “You can bridge the gap between data science and business stakeholders — a rare and valuable skill.”

---

## 🛠️ Technical Stack & Methodologies

| Area                  | Tools & Techniques                                                                 | Business Value                                  |
|-----------------------|------------------------------------------------------------------------------------|------------------------------------------------|
| **Machine Learning**  | Decision Trees, Random Forests, Classification Accuracy                           | Default prediction, risk scoring, automation   |
| **Data Sourcing**     | Kaggle dataset (Sandeep Bansode) — real-world, anonymized cardholder data          | Proven ability to find & validate external data |
| **Data Analysis**     | Demographic profiling (gender, education), EDA, insight generation                 | Customer segmentation, risk factor discovery   |
| **Model Evaluation**  | Accuracy metric, model comparison, selection justification                        | Model governance, performance benchmarking     |
| **Visualization**     | Pie charts, model comparison table, poster layout                                 | Executive briefings, stakeholder alignment     |
| **Domain Knowledge**  | Credit card mechanics, APR, limits, approval criteria, financial product types     | Regulatory compliance, product design, pricing |

---

## 📁 Repository Structure

```
├── CreditCard.Poster_10835879.10893087.pdf     # Professional poster (executive summary)
├── code/
│   ├── data_loading.py                          # Load and explore Kaggle dataset
│   ├── eda_gender_education.py                 # Generate demographic pie charts
│   ├── model_training.py                       # Train Decision Tree + Random Forest
│   └── model_evaluation.py                     # Compare accuracy, select best model
├── data/
│   └── credit_card_default.csv                 # Source dataset (3K rows, 25 cols)
├── screenshots/
│   ├── gender_pie_chart.png                    # 60.37% female defaulters
│   ├── education_pie_chart.png                 # 82.06% university/graduate defaulters
│   └── model_comparison_table.png              # DT 82.01% vs RF 81.50%
└── README.md                                   # You are here!
```

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/credit-card-default-prediction.git
   cd credit-card-default-prediction
   ```

2. Install Python dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

3. Run analysis scripts:
   ```bash
   python code/data_loading.py
   python code/eda_gender_education.py
   python code/model_training.py
   python code/model_evaluation.py
   ```

> ⚠️ Dataset sourced from Kaggle (Sandeep Bansode). Pre-cleaned version included.

## 📚 References & Tools

- **Dataset**: Sandeep Bansode, Kaggle — *Credit Card Default Prediction*  
- **ML Algorithms**:  
  - Decision Trees — IBM (2024)  
  - Random Forests — Biau, G. (2012)  
- **Financial Concepts**:  
  - Altman, E.I. (2013) — *Predicting Financial Distress*  
  - Visa, Mozo, Percival — Credit card definitions & mechanics  
- **Visualization**: Matplotlib, Seaborn — for pie charts and model comparison tables

---

## 🤝 Connect & Collaborate

👤 **Author**: [Your Name]  
📧 **Email**: [your.email@example.com]  
💼 **LinkedIn**: [linkedin.com/in/yourprofile]  
🎓 **Program**: MSc Data Science and Business Analytics, University of Plymouth

> 👉 *Open to roles in: Credit Risk Modeling, Fintech Analytics, Fraud Detection, Banking Data Science, Financial Product Management.*

---

✅ **Last Updated**: December 2023  
✅ **License**: MIT — Use, adapt, learn, and build upon this work!

---