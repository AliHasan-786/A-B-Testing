# A-B-Testing

## Overview
This project focuses on comparing the effectiveness of two advertising campaigns: a control campaign and a test campaign. The analysis involves examining various metrics such as number of impressions, website clicks, content viewed, products added to the cart, and purchases to determine which campaign is more successful.

## Dependencies
- Python
- Pandas
- Plotly

These libraries are utilized for data manipulation and interactive visualizations.

## Data
The dataset includes data from both control and test advertising campaigns, detailing metrics like the amount spent, impressions, reach, website clicks, and more.

## Preprocessing
The data is cleaned and preprocessed to correct column names and handle missing values. The missing values are filled using the mean of the respective columns.

## Model Training and Evaluation
This project does not involve traditional model training but focuses on descriptive analytics and comparative analysis between two different campaign strategies.

## Usage
1. Load the control and test group data.
2. Perform data preprocessing to prepare the datasets.
3. Analyze various metrics to compare the effectiveness of the campaigns.

## Results
The analysis involves:
- Comparing the number of impressions and amount spent between the campaigns.
- Evaluating user engagement metrics such as website clicks, content viewed, and products added to the cart.
- Assessing conversion rates in terms of purchases.
- Visualizing these comparisons using interactive Plotly graphs.

Through these analyses, the project aims to identify which campaign strategy is more efficient in terms of cost and user engagement, providing insights into better marketing practices.

## Note
Ensure the datasets (`control_group.csv` and `test_group.csv`) are available in the correct path to run the analysis.
