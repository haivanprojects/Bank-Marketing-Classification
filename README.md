# Bank Term Deposit Subscription Prediction

Business Context

Telemarketing campaigns are expensive and often result in low conversion rates. This project aims to build a classification model to predict whether a client will subscribe to a bank term deposit ('yes' or 'no'). By identifying high-potential customers, banks can optimize their marketing efforts and reduce wasted resources.

Dataset

The project uses the Bank Marketing dataset containing over 4,000 records of phone-based marketing campaigns.

- Features: Client demographics (age, job, education), previous campaign outcomes, and socio-economic indicators.

- Target Variable: y (binary: subscribed or not).

Technical Workflow

1. Data Preprocessing: Handled missing values, performed One-Hot Encoding for categorical variables, and applied Feature Scaling to normalize numerical data.

2. EDA (Exploratory Data Analysis): Identified key drivers for conversion, such as call duration and previous contact frequency.

3. Model Building: Implemented and compared three classification algorithms:

- Logistic Regression

- Decision Tree

- Random Forest

4. Evaluation: Used Accuracy, Precision, Recall, and F1-Score to determine the best-performing model.

Key Results

- The Random Forest model achieved the highest accuracy (approx. 90%), demonstrating its ability to handle complex interactions between features.

- High-potential leads were successfully segmented, allowing for a more targeted telemarketing strategy.

Project Files

`bank_marketing_classification.ipynb`: Full Python code for cleaning, analysis, and modeling.

`Bank_Deposit_Analysis_Report.pdf`: Detailed business report and methodology explanation.

`bank_marketing_dataset.csv`: Raw data utilized for the analysis.
