# ✈️ Flight Price EDA

A data exploration project focused on airfare variations and the factors influencing flight ticket pricing.

---

## 📌 Project Overview

This project conducts comprehensive exploratory data analysis (EDA) on flight booking data to understand how factors like airline, source-destination routes, departure time, stops, and duration impact ticket prices. It uncovers pricing patterns, outliers, and actionable business insights for airlines, travelers, and aggregators.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection
Dataset with flight records including airline, journey date, source, destination, departure/arrival time, stops, duration, and price.

### 2. Exploratory Data Analysis (EDA)
- Price distributions across airlines, routes, and stop counts
- Visualizations: departure time vs price, duration vs price, stops vs price
- Boxplots for airline/route/day/month price variations
- Correlation analysis for numerical features
- Outlier detection for high fares/short durations
- Categorical analysis: airline share, popular routes, stop patterns

### 3. Feature Engineering Insights
- Time features: day, month, weekday, hour from journey date
- Derived features: total duration, stop counts, duration categories
- Encoding: one-hot/label for categoricals
- Log-transformation for right-skewed price distribution

### 4. Key Analytical Findings
- More stops often mean lower prices (with route exceptions)
- Duration strongly correlates with higher prices
- Departure timing affects pricing by airline
- Premium airlines dominate high-demand routes
- Seasonal/weekday patterns influence fares

### 5. Business Insights & Recommendations
- **Travelers:** Book early, off-peak, fewer stops for savings
- **Airlines:** Optimize stop-heavy route pricing
- **Platforms:** Highlight value flights (stops + duration + timing)
- Foundation for predictive price modeling

---

## 📁 Project Structure
```
Flight-Price-EDA/
│── data/
│── notebooks/
│── src/
│── README.md
│── requirements.txt
```
---

## 📈 Key Findings
- Duration/stops are strongest price predictors
- Time features reveal booking patterns
- Right-skewed prices; log-transform recommended
- Outliers suggest premium segments/data issues
- Visual+statistical analysis enables pricing strategies

---

## 🚀 Future Improvements
- Predictive modeling (regression) for price forecasting
- Add booking lead time, seat class data
- Interactive Plotly/Streamlit dashboards
- External factors: holidays, fuel prices, competition
- Route-specific analysis (domestic vs international)

---

## 🧑‍💻 Author
**Data Science & Generative AI Enthusiast**  
Hyderabad, India

>
