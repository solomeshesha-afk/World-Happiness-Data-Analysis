# World Happiness Data Analysis (2015–2019)

## Project Overview
Analyzed 782 country-year observations from the World Happiness Report (2015–2019) using Python to investigate socioeconomic factors influencing life satisfaction, geographic patterns, and predictive modeling.

## Research Questions
- Which socioeconomic factors are most strongly associated with happiness?
- How did average happiness scores change from 2015 to 2019?
- What geographic and economic patterns appear across countries?
- Can machine learning predict happiness scores?

## Tools and Methods
- Python and Jupyter Notebook
- Pandas for data cleaning and merging datasets
- Correlation heatmaps, line charts, and scatter plots
- Random Forest regression and feature importance analysis
- Mean squared error (MSE) for model evaluation

## Key Findings
- Analyzed 782 country-year observations across five years.
- GDP per capita (r = 0.79) and healthy life expectancy (r = 0.74) showed strong positive correlations with happiness scores.
- 235 of 782 observations (30.1%) had happiness scores of 6 or higher on a 0–10 scale, using a project-defined threshold for high life satisfaction.
- Higher-income countries generally reported higher happiness scores, with visible geographic and socioeconomic differences.
- Random Forest regression achieved a mean squared error (MSE) of approximately 0.28.

## Project Files
- `FinalProject.ipynb` — Python analysis and visualizations
- `FinalProject.html` — rendered project notebook
- `DATS presentation.pdf` — research presentation

## Limitations
- Country-year observations are not individual survey respondents or population-weighted estimates.
- The score threshold of 6 is an analytical choice, not an official happy/unhappy classification.
- The analysis covers only 2015–2019, and missing-value handling may affect results.

## Conclusion
Economic conditions, health, and other socioeconomic factors are associated with differences in reported life satisfaction. This project demonstrates how Python, statistical visualization, and machine learning can be used to investigate global well-being.
