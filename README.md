# 🧠 Stakeholder Sentiment & Risk Analysis

This project demonstrates how **qualitative stakeholder feedback** can be transformed into **decision-ready intelligence** using sentiment analysis and stakeholder risk framing.

The focus is not NLP experimentation, but **stakeholder management, adoption risk, and delivery impact**.

---

## 🔍 Business Problem

Organizations collect large volumes of stakeholder feedback, but often fail to answer:

- Who is dissatisfied?
- Why are they dissatisfied?
- Which groups pose the highest delivery or adoption risk?

This project bridges that gap by combining **sentiment analysis, aggregation, and time-based signals**.

---

## 📊 Dataset

- **Type:** Synthetic stakeholder feedback data (privacy-safe)
- **Fields:**
  - Department  
  - Date  
  - Comment  
  - Theme  

---

## 🧠 Methodology

### 1️⃣ Sentiment Scoring
- Used **VADER sentiment analysis**
- Classified feedback into:
  - Positive
  - Neutral
  - Negative

---

### 2️⃣ Department-Level Aggregation
- Sentiment percentages calculated per department
- Normalization applied to ensure fair comparison

---

### 3️⃣ Time-Based Trend Analysis
- Monthly tracking of negative sentiment
- Identifies emerging risk patterns rather than static complaints

---

### 4️⃣ Qualitative Signal Extraction
- Word clouds generated for:
  - Positive feedback
  - Neutral feedback
  - Negative feedback
- Helps explain *why* sentiment exists, not just *what* it is

---

## 📈 Outputs & Visuals

- **Stacked bar chart:** Sentiment by department (%)
- **Donut chart:** Overall sentiment distribution
- **Line chart:** Monthly negative sentiment trend
- **Word clouds:** Key themes by sentiment
- **CSV exports:**
  - sentiment_by_department_percent.csv
  - sentiment_overall_percent.csv
  - top_themes_by_dept.csv

---

## 🔑 Key Insights

- Sentiment risk is **not evenly distributed** across departments
- Rising negative sentiment often appears **before delivery issues**
- Theme analysis explains dissatisfaction drivers, not just intensity

---

## 🛠️ Tools Used

- Python
- pandas, numpy
- nltk (VADER)
- matplotlib
- wordcloud

---

## 🎯 Why This Project Matters

This project demonstrates:
- Stakeholder-centric analytics
- Translation of unstructured text into risk signals
- Decision support for leadership and delivery teams
- Practical NLP applied to business problems

---

## ▶️ How to Run

1. Clone this repository  
2. Open the notebook in Google Colab or Jupyter  
3. Upload the CSV file  
4. Run all cells to reproduce charts and outputs  

---

## 👤 Author

**Mahesh Tanniru**  
Business Analyst | Healthcare Analytics | Stakeholder & Decision Intelligence  

- LinkedIn: https://www.linkedin.com/in/mahesh-tanniru  
- GitHub: https://github.com/Maheshtanni  
