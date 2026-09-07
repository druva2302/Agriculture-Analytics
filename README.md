# Agriculture Analytics – Seasonal Performance Analysis

## 📌 Project Overview

This project analyzes agricultural performance across **4,000 farms** to understand how crop selection, season, irrigation method, environmental conditions, agricultural inputs, location, production, revenue, and costs influence yield and profitability.

The analysis combines exploratory data analysis, correlation analysis, grouped business metrics, pivot tables, visualizations, profitability analysis, water-efficiency analysis, and an executive dashboard.

## 🎯 Business Objectives

- Identify the most profitable crops.
- Compare agricultural performance across seasons.
- Evaluate irrigation methods using yield, profit, and water efficiency.
- Compare state-level agricultural performance.
- Identify important agricultural input relationships with yield.
- Identify the strongest listed drivers of profit.
- Find reliable state + crop + irrigation combinations.
- Translate analytical findings into business recommendations.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab
- Exploratory Data Analysis
- Correlation Analysis
- Data Visualization
- Business Analytics

## 📊 Key Results

| Metric | Finding |
|---|---|
| Farms analyzed | 4,000 |
| Overall average yield | 5.27 tonnes/ha |
| Overall average profit | ₹111,556.46 |
| Most profitable crop | Sugarcane |
| Sugarcane average profit | ₹817,187.99 |
| Highest-profit irrigation method | Drip |
| Drip average profit | ₹219,626.00 |
| Drip average yield | 6.62 tonnes/ha |
| Highest water efficiency | Rainfed – 7.56 tonnes per 1,000 m³ |
| Best reliable state + crop + irrigation | Gujarat + Sugarcane + Drip |
| Best reliable combination margin | 70.15% |
| Strongest listed positive yield input correlation | Nitrogen – 0.054 |
| Strongest listed profit correlation | Revenue – 0.887 |

## 🔎 Major Business Insights

1. **Sugarcane is the strongest crop by average profitability**, with average profit of ₹817,187.99 per farm and average yield of 46.94 tonnes/ha.
2. **Drip irrigation has the highest average yield and average profit** among the analyzed irrigation methods.
3. **Rainfed irrigation has the highest water-efficiency metric**, so profitability and resource efficiency should be considered together rather than using a single KPI.
4. **Punjab has the highest average profit among the analyzed states.**
5. **Gujarat + Sugarcane + Drip** is the strongest reliable state–crop–irrigation combination by profit margin at 70.15%.
6. **Nitrogen has the strongest listed positive correlation with yield among the agricultural inputs analyzed.**
7. **Revenue has the strongest correlation with profit (0.887)**, followed by Production (0.554) and Yield (0.490).
8. Sugarcane and Chilli show strong profitability and margins, while Wheat, Rice, and Maize require closer investigation because their average profits are negative in the analyzed dataset.

## 📈 Dashboard

The final notebook contains an executive dashboard covering:

- Average Profit by Crop
- Average Yield by Irrigation Method
- Average Profit by State
- Average Profit by Crop × Irrigation Method

## 💡 Final Business Recommendation

Farm-level decisions should balance **profitability, yield, and water efficiency**. High-performing crop and irrigation combinations should be prioritized, while low-profit crops should be investigated for production costs, market pricing, and resource allocation.

## 📁 Project Structure

```text
Agriculture-Analytics/
├── README.md
├── Agriculture_Analytics_Final.ipynb
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
├── images/
│   └── dashboard.png
└── requirements.txt
```

## ▶️ How to Run

### Google Colab
Upload the notebook and dataset to Google Colab, then run the notebook from top to bottom.

### Local Jupyter

```bash
pip install -r requirements.txt
jupyter notebook Agriculture_Analytics_Final.ipynb
```

## 🔗 Original Google Colab

https://colab.research.google.com/drive/1pDBMrQl8ZYDTbFLizx7ks69Jh2bSeD_D?usp=sharing

## 👤 Portfolio Use

This project demonstrates practical skills in:

- Data cleaning and validation
- Exploratory data analysis
- Pandas groupby and aggregation
- Pivot tables
- Correlation analysis
- Data visualization
- KPI analysis
- Profitability analysis
- Business insight generation
- Executive dashboard creation
