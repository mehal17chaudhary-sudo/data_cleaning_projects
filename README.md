Raw_housing_dataset.csv :- original unprocesses datasets (CSV format).

Clean_housing_dataset.csv :- processes datasets ready for analysis (CSV format).

This dataset is prepare for the regression model.

Steps Performed :- 

1. Data Sampling:
Selected 7,500 representative samples out of 21,615 total records for efficient processing and analysis.


2. Duplicate Removal:
Identified and dropped duplicate entries to maintain clean and accurate data.


3. Feature Selection:
Removed unimportant and redundant columns that did not contribute to the analysis or model performance.


4. Feature Scaling & Encoding:
Converted values into standardized and encoded form using StandardScaler and appropriate encoding methods.


5. Feature Engineering:
Created new derived columns to enhance data insights and model input, such as:

     a) price_log (log transformation of price)

     b) has_renovated (binary feature from renovation year)

     c) etc. (additional engineered or transformed features improving interpretability and model       effectiveness)
