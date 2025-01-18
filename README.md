# crimes_india
This repository hosts the project for the DSE 315 course, dedicated to an in-depth analysis of crime patterns in India. The project aims to identify geographic and temporal trends, explore correlations with socio-economic factors, and support evidence-based policy development.

# India Crime Analysis Project

## Authors
- Mrunal Pravin Kulkarni (22183)
- Darshana Srivathsan (22001)
- Prakash Kumbhakar (22241)

## Course
**DSE 315: Data Science in Practice**

## Project Overview
This project focuses on analyzing crime data in India from 2001 to 2013, visualizing crime trends, performing statistical analysis, and using machine learning models to make predictions. The analysis is conducted in a series of Jupyter Notebooks, each building on the previous step to gain deeper insights and model predictions.

## Project File Structure
Ensure that the following files are in the same directory as the Jupyter Notebooks:
- **`india(1).geojson`** (GeoJSON file for district-level geospatial data)
- **`crime.csv`** (Raw crime data)
- **`crimes_cleaned.csv`** (Cleaned crime data)

## IMPORTANT : HOW TO RUN CODES


## Sequence of Notebooks

### 1. `EDA.ipynb` - Exploratory Data Analysis
- **Purpose:** This notebook performs an initial exploration of the crime data to understand its structure, identify missing values, and visualize basic trends.
- **Overview:** Includes data cleaning, feature engineering, and basic visualizations such as histograms, bar charts, and scatter plots to explore crime trends over time and across different districts.

### 2. `STATS.ipynb` - Statistical Analysis
- **Purpose:** To conduct detailed statistical analysis on the crime data to identify key patterns and relationships.
- **Overview:** Utilizes statistical tests and methods like the Augmented Dickey-Fuller (ADF) test for stationarity, correlation analysis, and hypothesis testing to understand trends and significant features related to crime rates.

### 3. `GEO.ipynb` - Geospatial Analysis
- **Purpose:** This notebook focuses on mapping and visualizing the geographic distribution of crime data across Indian districts.
- **Overview:** Uses the `geojson` file to create geospatial plots and heatmaps. This visualization helps identify high-crime regions and understand the spatial relationships within the data.

### 4. `MLmodels.ipynb` - Machine Learning Models
- **Purpose:** To build and evaluate machine learning models for crime prediction and classification.
- **Overview:** Implements models like Linear Regression, K-Nearest Neighbors (KNN), and Gradient Boosting to predict the total number of crimes based on various features and identify top districts by crime rate. The notebook compares model performance to determine the best approach.

### 5. `Prediction.ipynb` - Crime Prediction
- **Purpose:** To use time series forecasting methods, such as ARIMA, to predict future crime rates.
- **Overview:** Includes preprocessing steps like stationarity checks and differencing, followed by ARIMA model training. The notebook provides insights into potential crime trends for 2014 to 2023 and supports decision-making for law enforcement and policy planning.

## Running the Project
1. Ensure all required data files (`india(1).geojson`, `crime.csv`, `crimes_cleaned.csv`) are in the same directory as the Jupyter Notebooks.
2. Open the Jupyter Notebook interface and start with `EDA.ipynb` to begin the analysis.
3. Follow the sequence from `EDA.ipynb` → `STATS.ipynb` → `GEO.ipynb` → `MLmodels.ipynb` → `Prediction.ipynb` to maintain logical flow.

## Prerequisites
- Python 3.x
- Required libraries: Pandas, NumPy, Matplotlib, Seaborn, GeoPandas, Scikit-learn, Statsmodels, and Jupyter Notebook.

Ensure that the Python environment is properly set up with these packages installed to run the notebooks smoothly.

To enhance the analysis and provide more in-depth insights, we have added functionality to generate additional CSV files in the India Crime Analysis Project. Specifically, the project now includes code that generates CSV files for ARIMA predictions, which forecast crime trends from 2014 to 2023, as well as a CSV listing districts with the highest murder rates. Additionally, we have incorporated a clustering analysis that identifies and saves districts with similar crime characteristics, providing valuable information on crime hot spots. These outputs are created using Python code snippets integrated into relevant notebooks, ensuring that users can seamlessly generate and analyze these supplementary files for further exploration and strategic planning.

## Conclusion
This project provides an end-to-end analysis of crime trends in India, from exploratory data analysis and statistical insights to geospatial mapping and predictive modeling. The results can support strategic planning for crime prevention and resource allocation.
