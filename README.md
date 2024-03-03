# IPhone Purchase Prediction

## Problem Statement
The increasing popularity of iPhone purchases has prompted many stores to seek ways to predict whether a customer will purchase an iPhone from their store based on gender, age, and salary.

## Prediction
The goal of this project is to predict whether a customer will purchase an iPhone or not.

## Model
Two classifiers, K Nearest Neighbour (KNN) and Decision Tree, have been implemented to predict iPhone purchases. 

## Data Analysis and Visualization
- Utilized pandas and seaborn for data cleaning, analysis, and visualization.
- Key Insights:
  1. 'Age' shows a significant correlation with the target variable 'Purchase iPhone,' whereas 'Salary' has a weak correlation.
  2. Females tend to purchase more iPhones than males.
  3. Elderly individuals are more likely to buy iPhones compared to younger people.
  4. Majority of iPhone purchases are made by individuals with salaries ranging from 20-30k and those earning over 1 lakh.

## Data Preprocessing
As we had one categorical variable ('Gender'), we used One Hot Encoding to transform it into numerical values.

## Model Tuning
For KNN, the optimal value of K was chosen using the Elbow method.
Decision Tree used entropy as a criterion, as it gave better results than Gini.

## Model Evaluation
In comparing K Nearest Neighbour (KNN) and Decision Tree classifiers, both models exhibit similar overall accuracy (83% for KNN and 82% for Decision Tree). However, KNN demonstrates slightly better precision, recall, and F1-score for both classes, indicating a slightly more balanced performance on the given dataset.

## Tableau Dashboard
A Tableau dashboard was created to provide an overall analysis of iPhone buyers.

![Dashboard 1](https://github.com/MuskanKhandelia/Iphone_Purchase_Prediction/assets/65664089/2eee9d9b-6c3c-4f41-95f8-d136a8d845a9)

https://public.tableau.com/views/Iphone_Buyer_Analysis/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

### Conclusion
This project successfully addresses the problem of predicting iPhone purchases, and the insights gained can be valuable for stores aiming to understand their customer base better.
