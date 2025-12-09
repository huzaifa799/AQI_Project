# 🌍 Air Quality Index (AQI) Analysis: Pakistan vs India (2022-2025)

## 📌 Project Overview
This project presents a comprehensive data analysis of global Air Quality Index (AQI) trends, with a specific focus on a comparative study between **Pakistan** and **India**. 

Spanning from **July 2022 to December 2025**, the analysis leverages historical data to identify pollution patterns, seasonal variations (such as the "fifth season" of smog), and health implications associated with air quality in these regions.

## 🎯 Objectives
* **Global Analysis:** Analyze worldwide AQI patterns to identify countries with the most critical air quality concerns.
* **Comparative Study:** Conduct a side-by-side comparison of air quality trends in Pakistan and India over a 3.5-year period.
* **Trend Identification:** Uncover seasonal patterns, year-over-year trends, and specific "winter crisis" periods.
* **Health Impact:** Categorize days based on AQI health status (e.g., Good, Hazardous) to assess public health risks.
* **Actionable Insights:** Provide data-driven recommendations for environmental policy and public awareness.

## 📂 Dataset Details
The analysis relies on the `AQI.csv` dataset found in this repository.

* **Filename:** `AQI.csv`
* **Source:** Global Air Quality Index Database
* **Time Period:** July 21, 2022 – December 4, 2025
* **Geographic Coverage:** 190+ countries
* **Total Records:** ~22,400 entries
* **Key Columns:**
  * `Date`: Date of observation (YYYY-MM-DD)
  * `Country`: Name of the country
  * `Status`: AQI Health Category (e.g., Good, Moderate, Unhealthy, Hazardous)
  * `AQI Value`: Numerical Air Quality Index value

## 🛠️ Tech Stack
* **Python 3.x**
* **Pandas:** Data cleaning, manipulation, and time-series analysis.
* **NumPy:** Numerical operations.
* **Matplotlib & Seaborn:** Data visualization (histograms, count plots, line charts).
* **Jupyter Notebook:** Interactive environment for analysis.

## 📓 Analysis Structure
The main analysis is contained in `Project_01.ipynb`, organized into the following sections:

1.  **Data Preprocessing:** Loading raw data, handling missing values, and converting date formats.
2.  **Exploratory Data Analysis (EDA):** Visualizing global AQI distributions and identifying top polluted countries.
3.  **Country-Specific Deep Dives:**
    * **Pakistan:** Detailed monthly and yearly breakdown of AQI trends.
    * **India:** Detailed monthly and yearly breakdown of AQI trends.
4.  **Comparative Analysis:** Side-by-side visualization of Pakistan vs. India to highlight differences in pollution intensity and duration.
5.  **Conclusion & Recommendations:** Summary of findings regarding industrial regulation and seasonal interventions.

## 🚀 How to Run
1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Install the required dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Ensure `AQI.csv` is in the same directory as the notebook.
4.  Open `Project_01.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
5.  Run all cells to generate the analysis and visualizations.

## 🔮 Future Research Opportunities
Based on the current analysis, the following areas are identified for future work:
1.  Correlation with meteorological data (temperature, wind speed, humidity).
2.  Analysis of specific air pollutants (PM2.5, PM10, NO₂, SO₂, O₃).
3.  Impact analysis of major events (festivals, lockdowns, industrial incidents).
4.  Predictive modeling for seasonal air quality forecasting.
5.  Economic impact assessment of poor air quality.

## 📞 Contact
* **Project Duration:** July 2022 - December 2025
* **Last Updated:** December 2025
* **Author:** Muhammad Huzaifa Khalid

---
*This analysis aims to support environmental policy decisions and increase public awareness regarding the critical issue of air pollution.*
