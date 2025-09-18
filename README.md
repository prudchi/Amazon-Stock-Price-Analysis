# Amazon-Stock-Price-Analysis

## Project Overview
This project analyzes the historical stock price data of **Amazon (AMZN)** using Python and Pandas.  
The objective was to uncover trends, volatility, and performance patterns over time, and to visualize stock returns and moving averages.

Dataset Source: [Amazon Historical Stock Prices – Kaggle](https://www.kaggle.com/)

---

## Tools & Libraries
- Python
- Pandas (data cleaning & manipulation)
- Matplotlib & Seaborn (visualization)
- Jupyter Notebook (Google Colab environment)

---

## Process
1. **Data Import & Cleaning**
   - Imported dataset from CSV.
   - Converted dates to correct datetime format.
   - Sorted dataset by date.

2. **Feature Engineering**
   - Calculated **daily returns**.
   - Calculated **moving averages** (short & long windows).

3. **Analysis**
   - Price trend visualization over time.
   - Volatility analysis to identify most unstable periods.
   - Highlighted periods of abnormal gains/losses.
   - Compared yearly performance.

4. **Visualization**
   - Line plots for price trends.
   - Moving averages overlay.
   - Daily returns distribution.
   - Highlighted high-volatility periods.

---

## Key Insights
- Amazon stock shows clear long-term upward momentum with notable volatility spikes.
- Certain years (e.g., [insert year from your analysis]) showed abnormal gains/losses tied to market events.
- Moving averages provided useful signals for trend detection.
- Volatility clustering was observed around [insert insights from your results].

---

## How to Use
1. Download the dataset from Kaggle or use the provided `Amazon_stock_data.csv` in `/data/`.
2. Open the Jupyter Notebook in `/notebooks/` (works in Google Colab).
3. Run the notebook to reproduce analysis and visualizations.

---

## Project Structure
- **/data/** → raw dataset  
- **/notebooks/** → Jupyter notebook with analysis  
- **/outputs/** → charts and visualizations  
