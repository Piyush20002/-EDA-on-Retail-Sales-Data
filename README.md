Data Analysis project -1
EDA on Retail Sales Data

Description:

In this project, I have worked with a dataset containing information about retail sales. The goal is to perform exploratory data analysis (EDA) to uncover patterns, trends, and insights that can help the retail business make informed decisions.

Key Concepts and Challenges:

Data Loading and Cleaning: Load the retail sales dataset.
Descriptive Statistics: Calculate basic statistics (mean, median, mode, standard deviation).
Time Series Analysis: Analyze sales trends over time using time series techniques.
Customer and Product Analysis: Analyze customer demographics and purchasing behavior.
Visualization: Present insights through bar charts, line plots, and heatmaps.
Recommendations: Provide actionable recommendations based on the EDA.

1. Dataset Overview:
- The dataset contains 1,000 transactions with 9 columns including transaction details, customer demographics, and sales information
- Data covers transactions from January 2023 to January 2024
- No missing values or duplicate rows were found

2. Customer Demographics:
- Gender Distribution:
  * Female customers: 51% (510)
  * Male customers: 49% (490)
  * Very balanced gender distribution

- Age Distribution:
  * Age range: 18-64 years
  * Mean age: ~41 years
  * Largest age group: 46-55 years (229 customers)
  * Age group distribution:
    - 46-55: 229 customers
    - 26-35: 205 customers
    - 36-45: 202 customers
    - 56-65: 195 customers
    - 18-25: 169 customers

3. Product Category Analysis:
- Three main product categories with total quantities sold:
  * Clothing: 894 units (35.6%)
  * Electronics: 849 units (33.8%)
  * Beauty: 771 units (30.6%)
- Relatively even distribution across categories

4. Sales Metrics:
- Average Purchase Value: $456.00
- Price Range:
  * Minimum: $25
  * Maximum: $500 per unit
- Quantity per Transaction:
  * Range: 1-4 items
  * Average: ~2.5 items

5. Purchase Patterns:
- Most transactions involved multiple items (mean quantity of 2.514)
- Price per unit varies significantly (std dev: ~$189.68)
- Total amount per transaction ranges from $25 to $2,000

6. Other Notable Observations:
- The data shows consistent sales activity throughout the year
- The correlation heatmap suggests relationships between:
  * Total Amount and Price per Unit
  * Quantity and Total Amount


