🌦️ Weather Trend Forecasting Report

📊 1. Dataset Overview

- Total Records: 58658
- Total Features: 41
- Available Columns: country, location_name, latitude, longitude, timezone, last_updated_epoch, last_updated, temperature_celsius, temperature_fahrenheit, condition_text...

---

🛠️ 2. Data Cleaning
✔️ Removed columns with over 50% missing values  
✔️ Filled numeric missing values with median and categorical values with mode  
✔️ Removed duplicates
✔️ Handled outliers using the IQR (Interquartile Range) method

---

🔎 3. Exploratory Data Analysis (EDA)

- Temperature vs Humidity: Negative correlation observed
- Pressure and Temperature: Moderate positive correlation
- Wind Speed vs Temperature: No strong relationship

---

🌍 4. Top 10 Hottest Countries
| Rank | Country | Average Temperature (°C) |
|------|---------|---------------------------|
| 1 | Saudi Arabia | 32.16 |
| 2 | Djibouti | 32.15 |
| 3 | Qatar | 32.12 |
| 4 | United Arab Emirates | 31.83 |
| 5 | Kuwait | 31.78 |
| 6 | Chad | 31.55 |
| 7 | Sudan | 31.41 |
| 8 | Niger | 31.41 |
| 9 | Inde | 31.20 |
| 10 | Central African Republic | 31.17 |

---

🤖 5. Forecasting Models
| Model | RMSE | R² |
|---------------------|------|------|
| **Random Forest** | 7.30 | 0.29 |
| **Gradient Boosting** | 7.17 | 0.31 |
| **Ensemble Model** | 7.06 | 0.34 |

---

🌟 6. Feature Importance
| Feature | Importance |
|---------------|------------|
| **Humidity** | 0.42 |
| **Pressure** | 0.33 |
| **Wind Speed** | 0.25 |

---

💡 7. Recommendations
✅ Continue monitoring outliers for possible data entry errors.  
✅ Use the **ensemble model** for more accurate long-term forecasts.  
✅ Incorporate more environmental and seasonal data to improve accuracy.

---

🚀 8. How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Weather-Forecasting.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

---
