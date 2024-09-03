# Housing Price Prediction

This project aims to predict housing prices using a dataset that includes various features related to housing. The project involves data cleaning, exploratory data analysis, and linear regression modeling using both scikit-learn and statsmodels libraries.

## Project Overview

1. **Data Exploration and Visualization**:
   - Load and inspect the housing dataset.
   - Explore data types, missing values, and categorical variables.
   - Generate descriptive statistics and visualize data distributions using histograms and scatter plots.

2. **Data Cleaning**:
   - Handle missing values and convert categorical variables into dummy variables.

3. **Model Training**:
   - Split the data into training and testing sets.
   - Train a linear regression model using scikit-learn.
   - Evaluate model performance and visualize residuals.

4. **Advanced Modeling**:
   - Fit the linear regression model using statsmodels.
   - Analyze and interpret the model summary.

## Getting Started

### Prerequisites

Ensure you have the following Python packages installed:
- pandas
- numpy
- matplotlib
- scikit-learn
- statsmodels

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels
```

## Data Description

The dataset `housing.csv` contains the following columns:

- `longitude`: Longitude of the house.
- `latitude`: Latitude of the house.
- `housing_median_age`: Median age of the house.
- `total_rooms`: Total number of rooms.
- `total_bedrooms`: Total number of bedrooms.
- `population`: Total population.
- `households`: Number of households.
- `median_income`: Median income in the area.
- `median_house_value`: Median house value (target variable).
- `ocean_proximity`: Location category (e.g., NEAR BAY, INLAND).

## Notebook Overview

1. **Import Libraries**: Imports the necessary libraries for data manipulation, visualization, and modeling.

2. **Load Data**: Loads the housing data from the `housing.csv` file and inspects its basic structure.

3. **Data Exploration**: Explores the dataset to understand its structure, check for missing values, and view distributions of categorical variables.

4. **Descriptive Statistics and Visualization**: Generates summary statistics and visualizes the data using histograms and scatter plots.

5. **Data Cleaning**: Handles missing values and converts categorical variables into dummy variables.

6. **Train-Test Split**: Splits the data into training and testing sets.

7. **Train Linear Regression Model**: Fits a linear regression model using scikit-learn and evaluates its performance. Displays the intercept, coefficients, and R-squared value.

8. **Plot Residuals**: Visualizes the residuals to assess model performance.

9. **OLS Model with Statsmodels**: Fits the OLS model using the statsmodels library and displays the summary.

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd housing-price-prediction
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook housing_price_prediction.ipynb
   ```

4. Follow the instructions in the notebook to run the analysis.
