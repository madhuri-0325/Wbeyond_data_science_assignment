# Wbeyond_data_science_assignment
Sales Forecasting
# Sales Forecasting Project

## Overview

This project aims to forecast future sales using historical sales data, store information, oil prices, holiday events, and transaction data. The project involves data processing, feature engineering, model selection, and evaluation.

## Data

The project utilizes the following datasets:

- `train.csv`: Historical sales data used for training the model.
- `test.csv`: Data for which sales need to be forecasted.
- `stores.csv`: Information about the stores.
- `oil.csv`: Daily oil prices.
- `holidays_events.csv`: Information about holidays and events.
- `transactions.csv`: Daily transaction data.
- `sample_submission.csv`: Sample submission file.

These datasets should be placed in the `/content/sample_data/sales_forecasting/` directory.

## Running the Scripts

1. **Data Processing and Feature Engineering:** This step involves cleaning, transforming, and engineering features from the raw data. This is done in the main script.

2. **Model Selection and Forecasting:** The script trains and evaluates several forecasting models, including Naive Forecasting, Random Forest Regressor, XGBoost, and ARIMA. The best-performing model is selected for forecasting future sales.

3. **Evaluation:** The script evaluates the selected model's performance using metrics like Mean Absolute Error (MAE).

4. **Forecasting Future Sales:** The script uses the chosen model to forecast sales for the test dataset.

5. **Submission:** The script generates a submission file in the required format for evaluation.


## Output

The project generates the following outputs:

- `submission.csv`: Contains the forecasted sales for the test dataset.

## Note

- Make sure to have the necessary datasets in the specified directory structure.
- Adjust file paths and hyperparameters as needed.
