# California Housing Price Prediction using Multiple Linear Regression

## Project Description
This mini-project explores the California Housing dataset to analyze key factors affecting house prices and build a predictive model using multiple linear regression. The project includes data exploration, visualization, feature analysis, and model assessment to understand patterns in housing prices.

## Dataset
- **Source:** California Housing dataset
- **Features:**
  - Median Income
  - House Age
  - Number of Rooms
  - Number of Bedrooms
  - Population
  - Households
  - Latitude
  - Longitude
- **Target:** Median House Value

## Workflow

1. **Data Overview**
   - Examined dataset structure, missing values, and summary statistics.
   
2. **Data Visualization**
   - Histograms and boxplots to understand feature distributions and detect potential outliers.
   - Hexbin plots to visualize relationships between each feature and the target.
   - Correlation matrix to examine linear relationships among features.

3. **Feature Analysis**
   - Checked for multicollinearity to ensure model reliability.

4. **Modeling**
   - Built a pipeline including preprocessing and multiple linear regression.
   - Applied cross-validation to evaluate model performance.

5. **Model Assessment**
   - Evaluated using RMSE and R² metrics.
   - Interpreted feature importance.

## Key Findings
- Median income shows the strongest positive correlation with house prices.
- Some features exhibit moderate multicollinearity, which was addressed in preprocessing.
- The multiple linear regression model achieved:
  - **RMSE ≈ 0.75 (~$75k)** — average prediction error
  - **R² ≈ 0.576** — explains ~57.6% of the variance in house prices

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/er10ic24-ui/California-House-Price-Analysis.git

![Boxplot Example](images/boxplot.png)
![Hexbin Example](images/hexbin_MedOnc.png)
