# AI-ML-Tasks_HussainAbdullah
This repository contains completed AI/ML internship tasks using Python and Jupyter Notebooks.

---

## Task 1: Dataset Exploration & Visualization

### Objective
Explore and visualize the Iris dataset to understand the relationships between features and classes using pandas, seaborn, and matplotlib.

### Dataset Used
- Iris Dataset (built-in from `sklearn.datasets`)

### Key Steps
- Loaded dataset using `sklearn.datasets.load_iris`
- Converted to a pandas DataFrame
- Performed exploratory data analysis
- Visualized distributions and feature relationships with pair plots, histograms, and boxplots

### Key Findings
- Petal length and width are strong indicators of species.
- Setosa is easily separable, while Versicolor and Virginica overlap in some dimensions.

---

## Task 2: Stock Price Prediction (AAPL)

### Objective
Build a regression model to predict Apple Inc. (AAPL) stock prices using historical data.

### Dataset Used
- Historical stock data downloaded using `yfinance` for 2023.

### Model Used
- `RandomForestRegressor` from `sklearn.ensemble`

### Key Steps
- Downloaded 2023 AAPL stock data
- Engineered features like Open, High, Low, Close, Volume
- Trained Random Forest Regression model
- Evaluated performance using RMSE

### Key Results
- RMSE was reasonable for a simple model
- Stock price movements follow complex patterns — further improvement may include time series models like LSTM

---

## Task 6: House Price Prediction

### Objective
Predict house prices using selected features from a housing dataset.

### Dataset Used
- Custom dataset with the following columns:
  ```
  ['Id', 'Area', 'Bedrooms', 'Bathrooms', 'Floors', 'YearBuilt', 'Location', 'Condition', 'Garage', 'Price']
  ```

### Model Used
- `LinearRegression` from `sklearn.linear_model`

### Key Steps
- Selected numeric features: Area, Bedrooms, Bathrooms, Floors
- Preprocessed data
- Trained a linear regression model
- Evaluated performance with RMSE

### Key Results
- Simple linear regression gave a basic estimate of housing prices
- Accuracy could be improved by including categorical encoding (Location, Condition) or switching to more advanced models

---

## Setup

### Required Libraries:
```bash
pip install pandas matplotlib seaborn scikit-learn yfinance
```

### How to Run:
1. Open `.ipynb` files in Jupyter Notebook or VS Code.
2. Run all cells.
3. Inspect visualizations and model evaluation results.

---

## Submission Checklist (Done)

- [x] Jupyter notebooks with all code and explanations
- [x] Code is modular, clean, and commented
- [x] README with summary of tasks, models, and results
- [x] To be submitted via GitHub and Google Classroom

---

## Author

- **Hussain Abdullah - DHC-456 - AI/ML**
