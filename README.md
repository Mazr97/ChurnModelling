# Churn Modelling

This project is about predicting customer churn using a dataset of bank customers. The dataset includes information about the customer's credit score, geography, gender, age, tenure, balance, number of products, whether they have a credit card, whether they are an active member, their estimated salary, and whether they exited (churned).

## Steps

1. **Data Loading**: Load the 'Churn_Modelling.csv' file.

2. **Data Preprocessing**: Drop unnecessary columns and encode categorical variables.

3. **Data Scaling**: Scale numerical features using MinMaxScaler.

4. **Data Splitting**: Split the data into training and testing sets.

5. **Model Building**: Build a Sequential model with two layers using TensorFlow.

6. **Model Training**: Train the model using the Adam optimizer and binary cross entropy loss function.

7. **Model Evaluation**: Evaluate the model's performance on the test set using accuracy, precision, recall, F1 score, and AUC-ROC.

## Results

The model achieved the following performance metrics on the test set:

- Accuracy: 0.715
- Precision: 0.715
- Recall: 0.473
- F1 Score: 0.570
- AUC-ROC: 0.714

## Conclusion

The model performs well in predicting customer churn. It demonstrates better than random chance accuracy, with notable strengths in precision. The model effectively identifies customers who are likely to churn, providing valuable insights that can be used to inform customer retention strategies. This project showcases the potential of machine learning in understanding customer behavior and informing business decisions.
