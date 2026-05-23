# COVID-19 India: Comprehensive Data Analysis & Trends

This project provides an in-depth, data-driven analysis of the COVID-19 pandemic's impact across India. Using a variety of data sources and advanced visualization libraries, this notebook tracks the spread, mortality, and recovery trends of the virus.

## Project Overview
The main focus of this notebook is to analyze the spread trend of COVID-19 in India, starting from the first reported case in Kerala on January 30, 2020. It includes:
- **Historical Context**: A detailed timeline of the virus's arrival and the subsequent national lockdown.
- **Symptom Analysis**: Visualizing the most common symptoms (Fever, Dry Cough, Fatigue, etc.) based on global data.
- **Interactive Geospatial Mapping**: Using **Folium** and **Plotly** to create heatmaps and cluster maps of infected regions.
- **Time-Series Forecasting**: Utilizing **FBProphet** to predict future trends and peaks.
- **Real-time Data Scraping**: Extracting the latest statistics from official health ministry websites (MoHFW).

## Visualizations & Insights
The notebook features high-quality, interactive graphs including:
- **Symptom Distribution**: Bar charts showing the prevalence of various COVID-19 symptoms.
- **State-wise Case Tracking**: Comprehensive tables and maps showing confirmed, active, recovered, and death cases by state.
- **Testing Efficiency**: Analysis of ICMR testing data and positive-to-test ratios.
- **Growth Curves**: Logarithmic and linear plots of case escalation over time.

## Tech Stack
- **Language**: Python 3
- **Analysis**: Pandas, NumPy
- **Visualization**: Plotly Express, Plotly Graph Objects, Folium, Seaborn, Matplotlib, Altair
- **Prediction**: FBProphet
- **Scraping**: BeautifulSoup, Requests

## Author Note
**This project was completely done by me.** It represents a rigorous effort to synthesize complex epidemiological data into actionable visual insights.

## How to View
GitHub natively renders the `.ipynb` file, allowing you to **scroll through both the code and the interactive outputs** directly in your browser.

## Run in Google Colab
You can run the interactive version of this notebook directly in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oldregime/covid-19-india-analysis/blob/master/covid-19-india-analysis.ipynb)

---
*Data Source: MoHFW, ICMR, and Kaggle COVID-19 Datasets.*
