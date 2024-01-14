# iPhone Purchase Prediction

## Problem Statement
The increasing popularity of iPhone purchases has prompted many stores to seek ways to predict whether a customer will purchase an iPhone from their store based on gender, age, and salary.

## Prediction
The goal of this project is to predict whether a customer will purchase an iPhone or not.

## Model
We have created a K Nearest Neighbour Classifier model in Python, following all phases of the machine learning lifecycle.

## Data Analysis and Visualization
- Utilized pandas and seaborn for data cleaning, analysis, and visualization.
- Key Insights:
  1. 'Age' shows a significant correlation with the target variable 'Purchase iPhone,' whereas 'Salary' has a weak correlation.
  2. Females tend to purchase more iPhones than males.
  3. Elderly individuals are more likely to buy iPhones compared to younger people.
  4. Majority of iPhone purchases are made by individuals with salaries ranging from 20-30k and those earning over 1 lakh.

## Data Preprocessing
As we had one categorical variable ('Gender'), we used One Hot Encoding to transform it into numerical values.

## Choosing the Value of K
For selecting the value of K, the Error method/Elbow method was employed. The smallest error value was observed for k = 7. Thus, k = 7 was chosen for the model.

## Model Performance
The accuracy score of the model is 0.83. A confusion matrix was plotted, revealing that out of 95 predictions, 16 predictions were incorrect, and 79 were correct.

## Tableau Dashboard
A Tableau dashboard was created to provide an overall analysis of iPhone buyers.
Link - https://public.tableau.com/views/Iphone_Buyer_Analysis/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
![Tableau Dashboard](https://github.com/MuskanKhandelia/Iphone_Purchase_Prediction/assets/65664089/94e93dc0-8311-4ab4-a8cf-633e20b39f27)

### Conclusion
This project successfully addresses the problem of predicting iPhone purchases, and the insights gained can be valuable for stores aiming to understand their customer base better.
