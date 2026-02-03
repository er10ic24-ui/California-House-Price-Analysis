# California Housing Price Prediction using Linear Regression
This mini-project explores the California Housing dataset. The goal is to analyze the key features affecting house prices and build a multiple linear regression model to predict median house values. The project includes data exploration, visualization, feature analysis, and model assessment.

## Dataset

- Source: California Housing dataset
- Features include:
  - Median Income
  - House Age
  - Number of Rooms
  - Number of Bedrooms
  - Population
  - Households
  - Latitude
  - Longitude
- Target: Median house value

## Workflow

1. **Data Overview**
   - Checked dataset structure, missing values, and summary statistics

2. **Data Visualization**
   - Histograms and Boxplots to understand distributions
   - Hexbin plots to visualize feature-target relationships
   - Correlation matrix to examine linear relationships

3. **Feature Analysis**
   - Checked for multicollinearity among features

4. **Modeling**
   - Built a pipeline including preprocessing and multiple linear regression
   - Used cross-validation for model evaluation

5. **Model Assessment**
   - Evaluated using RMSE and R²
   - Interpreted feature importance
