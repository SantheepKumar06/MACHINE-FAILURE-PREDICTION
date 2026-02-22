🏭 Machine Failure Prediction using Machine Learning
Predictive Maintenance Classification Model
________________________________________
📌 Overview

Industrial machines often experience unexpected failures due to continuous operation and wear, resulting in production downtime and increased maintenance costs. Traditional maintenance approaches such as reactive and preventive maintenance are not always sufficient to prevent sudden breakdowns.
This project develops a Machine Learning–based classification model that uses sensor and operational data to:

•	Predict whether a machine will fail

•	Identify the type of failure

•	Enable proactive predictive maintenance

•	Reduce operational disruptions
________________________________________
🎯 Problem Statement
Unplanned machine failures lead to:

•	Increased production downtime

•	Higher repair and maintenance costs

•	Reduced operational efficiency

The objective of this project is to build a classification model that predicts machine failure in advance and categorizes the failure type to support data-driven maintenance decisions.
________________________________________
📊 Dataset Description
The dataset contains sensor and operational data collected from industrial machines.

<img width="625" height="232" alt="image" src="https://github.com/user-attachments/assets/88bce409-6608-4ff0-b582-b511e25a7782" />

________________________________________
🛠️ Project Workflow

1.	Data Pre-processing
   
2.	Exploratory Data Analysis (EDA)
   
3.	Handling Class Imbalance (SMOTE & Random Oversampling)
   
4.	Feature Engineering
	
5.	Model Training
    
6.	Model Evaluation
________________________________________
🤖 Machine Learning Models Used

•	Logistic Regression

• Decision Tree

• Gradient Boosting

•	AdaBoost

•	Artificial Neural Network (ANN)

Since this is an imbalanced dataset, resampling techniques were applied:

•	SMOTE

•	Random Oversampling (ROS200 & ROS3861)
________________________________________
📊 Results

Models were evaluated using:

•	Accuracy

•	Precision (Macro)

•	Recall (Macro)

•	F1-Score (Macro)

Models are ranked based on Macro F1-Score, as it provides a balanced evaluation across all failure classes.

🏆 Model Performance (Ranked by Macro F1-Score)

Rank	Model	Sampling	Accuracy	Precision	Recall	F1-Score

🥇 1	Gradient Boosting	ROS200
🥈 2	Gradient Boosting	ROS3861
🥉 3	ANN / MLP	ROS3861	

<img width="491" height="127" alt="image" src="https://github.com/user-attachments/assets/aed47198-dcbe-4f69-97d4-a9c37430c17c" />

________________________________________
📌 Key Insights

•	Gradient Boosting with ROS200 achieved the highest Macro F1-Score (0.7647).

•	Oversampling techniques significantly improved minority class detection.

•	Accuracy alone was not reliable due to class imbalance.

•	Ensemble models outperformed standalone decision tree models.
________________________________________
✅ Final Model Selection

Gradient Boosting with ROS200 was selected as the final model due to its superior balance between precision and recall across all failure classes.
________________________________________
🚀 Technologies Used

•	Python

•	Pandas

•	NumPy

•	Matplotlib

•	Seaborn

•	Scikit-learn

•	Jupyter Notebook
