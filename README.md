🌍 Air Quality Index (AQI) Analysis: Pakistan vs India (2022-2025)
📊 Project Overview
This project presents a comprehensive data analysis of global Air Quality Index (AQI) trends, with a specific focus on a comparative study between Pakistan and India. Spanning a period from July 2022 to December 2025, the analysis leverages historical data to identify pollution patterns, seasonal variations, and health implications associated with air quality in these regions.

🎯 Objectives
Global Analysis: Analyze worldwide AQI patterns to identify countries with the most critical air quality concerns.

Comparative Study: Conduct a side-by-side comparison of air quality trends in Pakistan and India over a 3.5-year period.

Trend Identification: Uncover seasonal patterns, year-over-year trends, and "winter crisis" periods.

Health Impact: Categorize days based on AQI health status (e.g., Good, Hazardous) to assess public health risks.

Actionable Insights: Provide data-driven recommendations for environmental policy and public awareness.

📂 Dataset
The analysis is based on the AQI.csv dataset.

Source: Global Air Quality Index Database

Time Period: July 21, 2022 – December 4, 2025

Total Records: ~22,400 entries

Columns:

Date: Observation date (YYYY-MM-DD)

Country: Name of the country

Status: AQI Health Category (e.g., Good, Moderate, Unhealthy, Hazardous)

AQI Value: Numerical Air Quality Index value

🛠️ Technologies & Libraries
The project is implemented in Python using a Jupyter Notebook. Key libraries include:

Pandas: For data manipulation and time-series handling.

NumPy: For numerical computations.

Matplotlib & Seaborn: For creating static visualizations (histograms, box plots, time series lines).

📝 Analysis Workflow
The Project_01.ipynb notebook is structured into the following sections:

Data Preprocessing:

Loading raw data and converting the Date column to datetime objects.

Handling missing values and ensuring data consistency.

Exploratory Data Analysis (EDA):

Distribution of AQI values globally.

Count plots of AQI Status categories.

Identification of the Top 15 countries with the highest average AQI.

Country-Specific Analysis:

Pakistan: detailed monthly and yearly aggregations.

India: detailed monthly and yearly aggregations.

Comparative Analysis:

Overlaid time-series plots comparing daily AQI trends of Pakistan vs. India.

Side-by-side bar charts for yearly averages and status distributions.

Calculation of statistical differences (Mean, Max, Min AQI).

Conclusion & Recommendations:

Summary of findings regarding pollution spikes (e.g., smog season).

Policy suggestions for industrial regulation and seasonal interventions.

🔍 Key Findings
Pollution Intensity: The analysis highlights significant periods of "Hazardous" air quality, particularly during the winter months (October–December) for both countries.

Comparative Insight: Statistical summaries indicate differences in the intensity and duration of smog spells between the two nations, with specific data points highlighting peak pollution events in 2024-2025.

Global Context: The study contextualizes local pollution levels against global averages, identifying where these two nations stand in world rankings.

🚀 How to Run
Ensure you have Python installed with the required libraries:

Bash

pip install pandas numpy matplotlib seaborn
Place AQI.csv in the same directory as the notebook.

Open Project_01.ipynb in Jupyter Notebook or JupyterLab.

Run all cells to generate the analysis and visualizations.

📞 Contact
Project Duration: July 2022 - December 2025

Last Updated: December 2025
