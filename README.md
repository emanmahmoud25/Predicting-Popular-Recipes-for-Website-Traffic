

# Predicting Popular Recipes for Website Traffic

![DALL·E 2024-09-21 11 32 06 - A visual representation of a popular recipe prediction project, showing a block of recipe images on a website, with one recipe highlighted for high tr](https://github.com/user-attachments/assets/dcc9939c-a249-4aea-a3d4-34b151aafc0f)



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
4. **Model Evaluation**: Compared the models based on performance metrics such as accuracy and recall.
5. **Business Metric**: Developed a business metric to monitor the performance of the recipe selection process.

## Key Findings
- The model achieved an accuracy of **82%**, making it a valuable tool for predicting popular recipes.
[![accuracy](https://github.com/user-attachments/assets/1d6fe608-fe06-41ae-818c-27cea045a7f9)](https://github.com/user-attachments/assets/1d6fe608-fe06-41ae-818c-27cea045a7f9)

-  ![download](https://github.com/user-attachments/assets/c96f6702-f979-4b7a-b7db-9a1025853a42)


## Recommendations
- Implement the model to automatically select recipes for the homepage to maximize traffic.
- Regularly update the model with new data to improve its predictive accuracy.

## Tools Used
- Python (pandas, scikit-learn)
- Data Visualization (matplotlib, seaborn)
- Jupyter Notebooks
