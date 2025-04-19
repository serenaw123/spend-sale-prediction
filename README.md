# Project Overview:
## Objective
The goal of this project is to develop an accurate linear regression model to predict sales based on advertising budgets across three media channels: TV, Radio, and Newspaper. By analyzing the relationship between ad spend and revenue, we aim to identify which medium contributes the most to sales growth, allowing businesses to make data-driven marketing decisions.

## Dataset Description
The dataset consists of 200 observations with the following columns:

TV – Advertising budget allocated to television (in thousands of dollars).

Radio – Advertising budget allocated to radio (in thousands of dollars).

Newspaper – Advertising budget allocated to newspapers (in thousands of dollars).

Sales – Generated revenue (in thousands of dollars).

## Exploratory Data Analysis (EDA)
To understand spending patterns and their impact on sales, we applied measures of central tendency (mean, median, and mode). This allowed us to identify typical investment amounts and their influence on revenue. Additionally, we used histograms to visualize data distribution, revealing how frequently certain sales figures occur.

## Data Cleaning & Outlier Detection
To improve model accuracy, we applied denoising techniques such as:

Interquartile Range (IQR): Used to detect and remove extreme outliers.

Confidence Intervals: Helped filter irrelevant variations, highlighting the true relationship between media spending and sales.

## Model Development
We implemented a linear regression model to quantify the impact of TV, Radio, and Newspaper spending on sales. This method was chosen due to its ability to model linear relationships between independent variables (advertising budgets) and the dependent variable (sales).

## Model Evaluation
To assess model performance, we used performance metrics such as:

Mean Squared Error (MSE): Measures the average squared differences between actual and predicted sales values.

R² Score: Evaluates how well the model explains variance in sales data.

## Key Findings
TV advertising had the strongest correlation with sales, indicating that higher TV budgets generally lead to increased overall sales. 

Radio advertising also showed a positive impact on overall sales but was less significant than TV.

Newspaper advertising had the weakest correlation, suggesting diminishing returns from newspaper spending.

## Future work:
Due to time limitations, we were only able to compare the relationship between investment in TV advertisment and sales but not Radio or Newspaper. In the future, I would analyze the relationships between Newspaper and Radio to Sales to further deepen analysis. 

## Conclusion
Based on our findings, the client should prioritize TV and Radio advertising for maximizing sales, while reassessing newspaper ad spending. 

  
