# BIS_Assignment
# Investment Trend Analysis and Forecasting

## Overview
This project analyzes startup investment trends using a dataset from Kaggle. It includes data preprocessing, exploratory data analysis (EDA), statistical analysis, and forecasting future investments using ARIMA and SARIMA models.

## Dataset
- **Source:** Kaggle (adilshamim8/startup-growth-and-investment-data)
- **Features:**
  - `Startup Name`: Name of the startup
  - `Industry`: Industry category (e.g., Blockchain, SaaS, Edtech)
  - `Funding Rounds`: Number of funding rounds
  - `Investment Amount (USD)`: Total investment received
  - `Valuation (USD)`: Company valuation
  - `Number of Investors`: Total investors involved
  - `Country`: Location of the startup
  - `Year Founded`: Year the startup was established
  - `Growth Rate (%)`: Growth percentage

## Installation
### Prerequisites
Ensure you have Python installed with the following libraries:
```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn kagglehub
```

## Methodology
### 1. Data Preprocessing
- Handled missing values
- Applied **One-Hot Encoding** for categorical variables (Industry) to allow proper numerical analysis
- Checked for duplicates and removed them
- Standardized and transformed large numerical values for better visualization

### 2. Exploratory Data Analysis (EDA)
- **Investment by Industry:** Identified industries receiving the highest investments
- **Funding Trends Over Years:** Analyzed whether investments have increased over time
- **Outlier Detection:** Used boxplots and statistical methods to detect extreme investments
- **Visualization Improvements:** Converted numerical values into millions or billions for better readability

### 3. Forecasting Future Investments
- Used Linear Regression to predict future investment trends
- Used **ARIMA and SARIMA** models to predict future investment trends based on historical data
- Compared model performance and selected the best fit for investment forecasting

## Visualizations
Key plots included in the analysis:
- **Industry-wise Investment Distribution** (Bar chart)
- **Yearly Funding Trends** (Line graph)
- **Investment Amount Distribution** (Histogram with KDE)
- **Outlier Detection** (Boxplots)
- **Future Investment Forecasting** (ARIMA/SARIMA prediction plots)

## Usage
1. Clone the repository:
```bash
git clone https://github.com/kavishkafer/BIS_Assignment.git
cd BIS_Assignment
```
2. Run the data preprocessing and EDA scripts:
```bash
python main.py
```




## License
This project is licensed under the MIT License.

## Contact
For queries, feel free to reach out at [kavishkafernando64@gmail.com] or open an issue on GitHub.
