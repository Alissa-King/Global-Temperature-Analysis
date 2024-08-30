# Global Temperature Analysis

## Overview
This project analyzes global temperature data to explore trends in land and ocean temperatures over time and investigate potential relationships between them.

## Dataset
The analysis uses the `GlobalTemperatures.csv` dataset, which contains the following key variables:

- `dt`: Date of temperature recording (year-month-day)
- `LandAverageTemperature`: Average land temperature (°F)
- `LandAverageTemperatureUncertainty`: Uncertainty of land temperature measurements (%)
- `LandMaxTemperature`: Maximum land temperature (°F)
- `LandMinTemperature`: Minimum land temperature (°F)
- `LandAndOceanAverageTemperature`: Average land and ocean temperature (°F)

## Analysis

### 1. Exploratory Data Analysis (EDA)
- Histograms of key variables
- Descriptive statistics (mean, mode, spread, skewness)
- Probability Mass Functions (PMFs)
- Cumulative Distribution Functions (CDFs)

### 2. Hypothesis Testing
- Permutation tests for difference in means
- Correlation analysis

### 3. Regression Analysis
- Simple linear regression
- Multiple linear regression

## Key Findings
- Both land and ocean temperatures show notable increases over time.
- There is a strong correlation between land and ocean temperatures.
- However, hypothesis testing did not show a statistically significant relationship between land and ocean temperature increases.
- Regression models showed high multicollinearity between land and ocean temperatures.

## Limitations
- Limited data on external factors that might contribute to temperature increases.
- Missing data, particularly for ocean temperatures.
- Lack of contextual information (e.g., measurement locations, historical events) that could provide insight into outliers or trends.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- StatsModels

## Future Work
- Incorporate additional variables related to measurement locations and socioeconomic activities.
- Explore more advanced time series analysis techniques.
- Investigate regional variations in temperature trends.

## How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook Global_Temperature_Analysis.ipynb`

## Author
Alissa King

## License
This project is licensed under the MIT License.
