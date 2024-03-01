# Customer-Churn-prediction
Predicting the likelihood of a customer Churning or not by using Gradient Boost Classifier
In my recent venture into Telecom Churn Prediction, I harnessed the capabilities of diverse models, including Decision Tree, Logistic Regression, Random Forest, and Gradient Boosting. This journey unveiled the intricacies of customer behaviour, ultimately leading to a robust model with a staggering accuracy score of 98%.

Data Exploration and Initial Challenges:
At the outset, I encountered challenges as the models struggled to predict churning customers effectively, despite an admirable 76% accuracy in identifying loyal customers. Recognizing the imbalance in the data, I implemented Oversampling techniques to level the playing field.

Oversampling and Model Enhancement:
After Oversampling, a significant transformation ensued. All four models—Decision Tree, Logistic Regression, Random Forest, and Gradient Boosting—exhibited remarkable improvements in predicting both churning and non-churning customers. Notably, the Gradient Boosting classifier emerged as the frontrunner.

Evolution of Model Performance:
Here's a snapshot of the model's progression through key stages:

Model 
Before Oversampling
After Oversampling (Random Forest)
After SMOTTENN
After Hyperparameter Tuning
Accuracy Score
0.8234
0.8791
0.8845
0.9122
Precision (Churn - 1)
0.09
0.93
0.91
0.91
Recall 
(Churn - 1)
0.56
0.89
0.91
0.95
F1-Score (Churn - 1)
0.16
0.91
0.91
0.93


These metrics encapsulate the evolution of the model's performance, showcasing the substantial improvements achieved through strategic oversampling, balancing, and hyperparameter tuning. The remarkable balance between precision and recall in the final model underscores its prowess in deciphering complex patterns within telecom churn dynamics.
