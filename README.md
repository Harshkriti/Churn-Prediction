# Bank Churn Prediction
## A Data-Driven Approach to Improve Customer Retention

### Introduction
● Customer churn refers to the rate at which customers leave a company. 

● It is a significant problem for banks, leading to lost revenue and increased customer acquisition costs.

● Churn prediction models can help banks improve customer retention, reduce costs, and increase revenue, providing a competitive advantage in the industry.

### How can banks solve this customer churn problem and maintain a sustainable business model?

● Develop a predictive model that can identify customers at risk of churning.

● Understand the factors that contribute to customer churn. 

In this project, I have built these 3 models and compared their performances- 
1. Logistic Regression: It is a popular and interpretable model for binary classification problems like customer churn. The coefficients obtained from the model can provide insights into the factors influencing churn.
2. Random forest: It is an ensemble model that combines multiple decision trees to improve prediction accuracy. It can handle non-linear relationships and interactions between features effectively. Random forest can provide feature importance rankings, which help identify the key factors contributing to churn.
3. XGBoost: It is another powerful ensemble model known for its high predictive performance. It is an advanced gradient-boosting algorithm that often outperforms other models. Similar to random forest, XGBoost can provide feature importance information. Additionally, it offers various hyperparameters to tune the model's performance, such as learning rate, maximum depth, and regularization parameters.

The performance of these models was evaluated using :
1. AUC ROC (Area Under the Receiver Operating Characteristic Curve): It measures the model's ability to discriminate between positive and negative classes across various probability thresholds. A higher AUC ROC indicates better model performance. It represents the probability that a randomly chosen positive instance is ranked higher than a randomly chosen negative instance by the model.
2. Accuracy: It is the ratio of correct predictions to the total number of predictions. It provides a general overview of the model's overall performance.
3. Recall (Sensitivity or True Positive Rate): It measures the proportion of true positive predictions out of all actual positive instances. In the context of customer churn, it represents the ability of the model to correctly identify churned customers. A higher recall indicates that the model is effective at capturing customers who are at risk of churning.
4. F1 Score: It is the harmonic mean of precision and recall. It provides a balanced measure of a model's performance by considering both false positives and false negatives. F1 score is particularly useful when the classes are imbalanced or when there are costs associated with false positives and false negatives.

After conducting a thorough analysis and formulating recommendations, I developed a business action plan that emphasized the potential business outcomes.
