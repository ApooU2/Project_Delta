# Project_Delta


## combined.ipynb

Predicts the stock price and future prices based on a Deep Neural Network with LSTM modules. Metrics module included to see the deployment on static data which is fetched from yahoo finance (daily data).

The `combined.ipynb` notebook contains the core implementation for data preprocessing, analysis, and visualization. It integrates multiple steps into a single workflow for ease of use and reproducibility.

### Features
- **Data Preprocessing**: Handles missing values, normalization, and feature engineering.
- **Analysis**: Includes statistical summaries and exploratory data analysis (EDA).
- **Visualization**: Generates plots to help understand data trends and patterns.

### Usage
1. Open the notebook in Jupyter or any compatible environment.
2. Follow the step-by-step instructions provided in the notebook cells.
3. Modify parameters as needed to suit your dataset.

### Requirements
Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `tensorflow`
- `yfinance`
- `scikit-learn`

### Notes
- The notebook is designed to be modular, allowing users to run specific sections independently.
- For large datasets, consider optimizing memory usage in the preprocessing steps.
- Refer to the comments in the notebook for additional guidance.

### Future Directions
- Testing performance on live deployments (in-progress).
- Adding and Storing decay metrics based on live performance (change in market dynamic).
- Adding a module which analyzes the decay metrics stored and potentially do some feature engineering with it.
- Making the training data more fine-grained by using tick based data (usually paid).
- Ensemble Model approach with GARCH (for market volatility analysis) and or ARIMA (for time series processing). 
