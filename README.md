# 🌍 Life Expectancy vs GDP (2000–2015)
### A Data Analysis Portfolio Project by Rosana Cepeda

This project explores the relationship between a country’s **GDP** and **life expectancy** using data from the **World Health Organization** and the **World Bank** across six countries over a 15-year period.

---

## 📈 Project Overview

Using Python (Pandas, Seaborn, Matplotlib), I analyzed trends in GDP and life expectancy to answer the following:

- How have GDP and life expectancy changed from 2000 to 2015?
- Is there a global correlation between GDP and life expectancy?
- Do some countries benefit more from economic growth than others?

---

## 🌐 Dataset

- Source: WHO & World Bank via Codecademy
- CSV File: `all_data.csv`
- Countries: Chile, China, Germany, Mexico, United States, Zimbabwe
- Time Range: 2000–2015

---

## 🧠 Key Insights

- All six countries experienced rising life expectancy from 2000 to 2015.
- **Zimbabwe** showed the most significant improvement—from ~45 to 60 years.
- **China** saw a 10x GDP increase over the period.
- While the **overall correlation** between GDP and life expectancy was **moderate (0.34)**, **country-level correlations ranged from 0.91 to 0.98**, showing a much stronger internal relationship.
- A **linear regression model** showed an **R² of 0.12**, meaning GDP alone is not a strong global predictor of life expectancy.

---

## 🛠 Tools Used

- Python (Jupyter Notebook)
- pandas
- seaborn
- matplotlib
- scikit-learn

---

## 📂 Project Files

- `life_expectancy_gdp.ipynb` — Clean notebook with visuals, stats, and conclusions
- `all_data.csv` — Raw dataset
- `README.md` — This file

---

## 💡 Final Thoughts

This project highlights that while **GDP growth is important**, it's only part of the story. Countries with stronger infrastructure and healthcare systems may see more life expectancy gains per dollar of GDP growth than others.

---

## 🚀 Next Steps

- Add more predictors (e.g., education, healthcare spending)
- Try non-linear models or country clusters
- Create a dashboard using Plotly or Streamlit

---

👩‍💻 _First analysis shipped. Next up: mastering NLP, one dataset at a time 🌿💻_
