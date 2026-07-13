# Nigerian Macroeconomic Pipeline: Currency Devaluation & Inflation Dynamics

An empirical data engineering and econometric pipeline built to evaluate the quantitative relationship between national currency value (USD/NGN) and consumer price indexes (CPI) within Nigeria over a 24-year timeline (2000–2024). 

This repository serves as a portfolio project showcasing the practical intersection of **Computer Science (Data Pipeline Engineering)** and **Quantitative Economics (Time-Series Analytics)**, mapping directly to interdisciplinary frameworks like MIT's Course 6-14.

## 📊 Project Architecture

## ⚙️ 
## ⚙️ Core Technical Features
- **Automated Data Ingestion:** Programmatic API calling utilizing the `wbgapi` wrapper to extract multi-decade structural metrics from World Bank global servers directly into a computing dataframe.
- **Data Engineering Matrix:** Transposed dimensional layouts, converted automated index string formats into numerical date signatures, and executed linear interpolation workflows (`df.interpolate()`) to handle data sparsity.
- **Statistical Analytics:** Pearson correlation calculations mapping the velocity of currency devaluation directly against shifts in domestic consumer price inflation.
- **Predictive Modeling:** Multi-variable Linear Regression training via `scikit-learn` to isolate predictive indicators and quantify lag metrics within currency transmission mechanisms.
- **Dual-Axis Visualizations:** High-density time-series charts generated through `matplotlib` and `seaborn` plotting the long-term convergence of exchange rates and macroeconomic trends.

## 🛠️ Tech Stack & Dependencies
- **Languages:** Python 3
- **Environment:** Jupyter Notebook / Google Colab
- **Libraries:** `pandas`, `numpy`, `wbgapi`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`

## 📈 Analytical Observations & Hypotheses
The pipeline evaluates how closely the Nigerian consumer market tracks the **Purchasing Power Parity (PPP)** economic theory. 

Initial output indicators demonstrate a powerful, positive Pearson correlation coefficient between the rise of the NGN/USD exchange rate and localized inflationary trends. This suggests that the transmission mechanism between imported input costs and domestic retail pricing operates with high velocity, validating the economic theory of exchange rate pass-through within developing, import-reliant markets.

## 📂 Repository Contents
- `nigerian_macroeconomic_pipeline.ipynb`: Complete source code, complete data clearing workflows, machine learning executions, and graphical rendering pipelines.
- `README.md`: Executive research overview and pipeline documentation.

## 🚀 Future Scalability Roadmap
- Implement Autoregressive Integrated Moving Average (ARIMA) models to scale from basic linear regression to formal stochastic time-series forecasting.
- Integrate automated daily exchange rate web scrapers targeting open parallel market APIs to compare official bank rates against consumer reality metrics.

---
*Developed by Oluwademilade Taiwo as an independent quantitative research module.*
