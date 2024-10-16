

# Predicting Popular Recipes for Website Traffic

![recipe](https://github.com/user-attachments/assets/9bd206bc-b302-4b95-aea5-8a6a5c00f103)



## Project Overview
This project aims to predict which recipes will lead to high website traffic for a recipe discovery platform. The goal is to help the product team display popular recipes on the homepage, increasing site traffic and boosting subscription rates.

## Problem Statement
The challenge is to correctly predict recipes that will generate high traffic 80% of the time and minimize the chances of featuring unpopular recipes. More traffic results in higher subscriptions, which is critical for the business.

## Data
The dataset contains key features about recipes, including:
- **recipe**: Unique identifier for each recipe
- **calories, carbohydrates, sugar, protein**: Nutritional information
- **category**: Type of recipe (e.g., Lunch, Snack, Dessert)
- **servings**: Number of servings
- **high_traffic**: Whether the recipe generated high traffic (Yes/No)

## Methodology
1. **Data Cleaning**: Performed data validation and cleaning for all columns.
2. **Exploratory Data Analysis (EDA)**: Visualized the relationship between recipe attributes and website traffic using various charts.
3. **Model Development**: Built a machine learning model to predict high-traffic recipes based on their features.
   - Baseline model: [Describe baseline model]
   - Comparison model: [Describe comparison model]
     
   <img width="384" alt="compare" src="https://github.com/user-attachments/assets/f9a8cbff-14c1-44bf-bfa2-2e62991e1d5d">

     
4. **Model Evaluation**: Compared the models based on performance metrics such as accuracy and recall.
5. **Business Metric**: Developed a business metric to monitor the performance of the recipe selection process.

## Key Findings
- The model achieved an accuracy of **84%**, making it a valuable tool for predicting popular recipes.
 ![download](https://github.com/user-attachments/assets/a929905f-9161-458f-84d5-2f14e85c667a)

![number_r](https://github.com/user-attachments/assets/716bbba5-be04-49e5-b71f-9b4572df1093)


## Recommendations
- Implement the model to automatically select recipes for the homepage to maximize traffic.
- Regularly update the model with new data to improve its predictive accuracy.

## Tools Used
- Python (pandas, scikit-learn)
- Data Visualization (matplotlib, seaborn)
- Jupyter Notebooks
