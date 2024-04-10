# Predictive Analysis of Health Service Demand

## Overview
This predictive analytics project focuses on forecasting the demand for health services by analyzing past trends using time-series models. The aim is to facilitate strategic planning and resource management for services like 'Home Care' and 'Mental Health', segmented by geographical zones.

## Features
- **Time-Series Forecasting**: Applied SARIMAX models to predict future service demands.
- **Categorization**: Predictions are categorized by service type and geographical zones.
- **Data Preprocessing**: Developed comprehensive scripts for data cleaning and transformation.
- **Trend Analysis**: Conducted trend analysis to offer strategic business recommendations.

## Installation
Clone the repository and install the required Python dependencies. Additionally, install the latest version of Power BI Desktop for visual analytics.

```bash
git clone https://github.com/anush97/city_hosp_forecasting.git
cd city_hosp_forecasting
pip install -r requirements.txt
```

## Usage
The Jupyter notebooks within the `notebooks` directory contain all the analyses:

```bash
cd notebooks
jupyter notebook
```

## Data
Historical health service visit data, including client cities, service types, and employee assignments, are pre-processed for modeling.

## Methodology
- **Data Preparation**: Leveraged Python for extracting and cleansing data from various formats, including CSV and JSON.
- **Predictive Modeling**: Developed time-series forecasting models, taking into account seasonal variations and trends.
- **Performance Assessment**: Evaluated model predictions with RMSE and provided visualizations of forecasted demands.
- **Strategic Analysis**: Utilized trend analysis to formulate recommendations for resource allocation.

## Results
The project's predictive models successfully estimate future health service demands, enabling informed decisions for resource distribution. The findings are detailed in the `reports` section of this repository.

## Skills and Tools Used
- **Data Science**: Engaged in advanced data manipulation and analysis, showcasing skills in pandas, numpy, and statsmodels.
- **Machine Learning Engineering**: Implemented and tuned time-series forecasting models, demonstrating proficiency in predictive analytics.
- **Data Visualization**: Used matplotlib and seaborn for graphical representation of data and forecasts.
- **Data Engineering**: Handled data cleaning, feature extraction, and transformation to prepare datasets for modeling.
- **Tools**: Employed tools like Google Colab for model development, Power BI for dashboards, and Git for version control.

## Conclusion
Through meticulous data processing, modeling, and trend analysis, this project reflects my comprehensive approach to tackling complex predictive modeling tasks. It underscores my aptitude in applying data science and machine learning techniques to derive insights that drive strategic business decisions in the healthcare services sector.
