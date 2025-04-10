# Diamond Price Analysis and Forecasting

## Project Description
This project focuses on analyzing diamond prices based on their characteristics (carat, cut, color, clarity, etc.) and building a predictive model to estimate diamond prices.

**Goal**: Predict diamond prices using machine learning (Regression).  
**Dataset**: `diamonds.csv` [from Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds) – contains 53,940 diamonds with features like:

- **Carat**: Carat weight of the diamond.
- **Cut**: Describe cut quality of the diamond. Quality in increasing order Fair, Good, Very Good, Premium, Ideal.
- **Color**: Color of the diamond, with D being the best and J the worst.
- **Clarity**: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)).
- **depth %**: The height of a diamond, measured from the culet to the table, divided by its average girdle diameter.
- **table %**: The width of the diamond's table expressed as a percentage of its average diameter.
- **Price**: the price of the diamond.
- **X**: length mm.
- **Y**: width mm.
- **Z**: depth mm.

## Environment Setup
The project uses the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- plotly
- scikit-learn (for machine learning models)

## Data Wrangling
The dataset was loaded and inspected for:
- Missing values
- Inconsistent data types
- Duplicated rows
- Columns to be dropped or re-parsed

### Key Findings:
- The dataset has 53,940 rows and 11 columns.
- No missing values or duplicated rows were found.
- The column 'Unnamed: 0' was renamed to 'index' for clarity.

## Exploratory Data Analysis (EDA)
The EDA phase involved analyzing the relationship between diamond characteristics and their prices. Key visualizations and insights include:
- Distribution of diamond prices
- Correlation between carat and price
- Impact of cut, color, and clarity on price

## Machine Learning Models
Two regression models were implemented:
1. **Linear Regression**
2. **Random Forest Regressor**

## Built with:
| Tools 		|
| -------- 		|
| Jupyter Notebook	|
| Python	   	|
| Pandas		|
| Numpy			|
| plotly		|
| sklearn |
