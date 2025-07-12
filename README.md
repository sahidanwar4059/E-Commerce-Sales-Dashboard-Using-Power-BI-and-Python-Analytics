
# 🛍️ Online Retail Store Sales Analysis – Expansion Strategy 

This project was created as part of a business analytics task to support the CEO and CMO of an online retail store in making data-driven decisions to expand operations. The goal was to answer specific executive questions through effective data visualization using Power BI, following detailed data cleaning using Python.

---

## Background

The CEO and CMO of an online retail store wanted to understand revenue trends, customer value, and country-wise performance to assist in making strategic expansion decisions. The executives provided four key business questions that needed to be addressed with clear visuals.

---

## 🧾 Executive Requirements

1. **CEO:** View monthly revenue trends for 2011 to identify seasonal patterns.
2. **CMO:** Analyze the top 10 countries (excluding UK) by revenue and quantity sold.
3. **CMO:** Identify top 10 customers by revenue to enhance customer retention.
4. **CEO:** Understand country-wise demand (excluding UK) to prioritize expansion regions.

---

## 🧹 Data Cleaning Process

Performed in the Jupyter notebook using pandas:
- Removed rows with Quantity < 1
- Removed rows with Unit Price < 0
- Filtered out cancelled transactions (Invoices starting with 'C')
- Removed null Customer IDs and invalid rows
- Created new column: `TotalPrice = Quantity × UnitPrice`

---

## 📊 Tools Used

- **Python (Jupyter Notebook)** – Data cleaning & preprocessing
- **Power BI** – Visual dashboard with four tabs (one for each question)
- **MS Word & PowerPoint** – Summary reports and presentation slides

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Online retail store Data Cleaning and Preprocessing.ipynb` | Python notebook for cleaning and feature engineering |
| `Online Retail Store Sales Dashboard.pbix` | Power BI file with four visual tabs |
| `Online_Retail_Insights_Report.docx` | Document summarizing insights |
| `Online_Retail_Visuals_Presentation.pptx` | Presentation slides for business review |
| `README.md` | Project overview and documentation |

---

## 🔍 Key Insights

- 📈 **Revenue peaks in November**; seasonal dip in January & December
- 🌍 **Top countries (excl. UK):** Germany, France, Netherlands
- 👥 **Top 10% customers drive over 60%** of total revenue
- 🧭 **Expansion opportunities** identified in consistent high-revenue countries
- 📦 Giftware and home decor are best-selling categories

---

## ✅ Recommendations

- Expand in Germany, France, and Netherlands
- Develop loyalty programs for top customers
- Track monthly demand patterns for better inventory management
- Exclude returns and cancellations to maintain data quality


---

## 👨‍💻 Author
 Sahid Anwar 
 E-mail-anwarkhanmothuka@gmail.com
 Linkdin-Sahid-Anwar4059
