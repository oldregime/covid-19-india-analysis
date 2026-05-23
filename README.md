# COVID-19 India: Comprehensive Data Analysis & Trends

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oldregime/covid-19-india-analysis/blob/master/covid-19-india-analysis.ipynb)

This project provides an in-depth, data-driven analysis of the COVID-19 pandemic's impact across India. Using a variety of data sources and advanced visualization libraries, this notebook tracks the spread, mortality, and recovery trends of the virus.

## 🚀 Key Features
- **Interactive Geospatial Visualizations**: Maps generated with `Folium` and `Plotly` to visualize regional impact.
- **Advanced Forecasting**: Utilizing the `Prophet` library for time-series prediction of confirmed cases and deaths.
- **Symptom Profiling**: Statistical breakdown of common COVID-19 symptoms.
- **Real-time Data Integration**: Scrapes current statistics from official health ministry sources.

## 📊 Visualizations Included
*(The notebook contains high-resolution interactive charts like these)*
- **Spread Trends**: Logarithmic growth curves and area plots showing the escalation over time.
- **Regional Heatmaps**: Interactive maps highlighting hotspots and clusters across Indian states.
- **Demographic Insights**: Gender and age-wise distribution of cases, recoveries, and mortality.

## 🛠️ Technical Fixes for Colab
I have updated this notebook to ensure it works perfectly in **Google Colab** (Python 3.12+):
- **Library Updates**: Migrated from the deprecated `fbprophet` to the modern `prophet` package.
- **Dependency Management**: Added automated `pip install` commands for `pycountry` and `prophet`.
- **Environment Awareness**: Added checks to handle data paths gracefully outside of Kaggle.

## 📋 Tech Stack
- **Languages**: Python 3
- **Visualization**: Plotly, Folium, Seaborn, Matplotlib, Altair
- **Data Science**: Pandas, NumPy, Scipy
- **Prediction**: Prophet (Meta Open Source)
- **Scraping**: BeautifulSoup4, Requests

## 🧑‍💻 Author Note
**This project was completely done by me.** It represents a rigorous effort to synthesize complex epidemiological data into a professional analysis suite.

---
### How to Run
1. Click the **Open in Colab** badge at the top.
2. Ensure you have the required datasets available in the `/kaggle/input` path (or update the paths in the data loading section).
3. Run all cells to see the interactive analysis.
