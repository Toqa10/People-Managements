# People-Managements
HR Risk Score Prediction App is a simple machine learning web application built with Streamlit. It allows HR managers and decision-makers to predict the risk score of employees based on their profiles.  
💼 Project Description – HR Risk Score Prediction App
This project is a Streamlit-based web application designed to help HR teams predict employee risk levels using machine learning.

The idea is to support data-driven decision-making in human resource management. HR departments can use this app to identify employees who are potentially at risk of leaving the company, underperforming, or needing extra support.

🧠 What does the app do?
The app takes basic employee information such as gender, job title, department, years of service (tenure), salary amount, and number of promotions. It uses this data to predict a risk score: whether the employee is low, medium, or high risk.

🔍 Why is this important?
Predicting employee risk helps companies:

Take early action to support or retain staff.

Prevent unwanted turnover.

Improve workforce planning and productivity.

Identify patterns related to performance or disengagement.

⚙️ How does it work?
The app uses machine learning (Random Forest Classifier).

It cleans the data and encodes any text features (like gender and job title).

It solves the class imbalance problem using SMOTE (a technique that balances the dataset).

The model is trained and evaluated, and the results are displayed in the app.

You can enter employee details in the app and instantly see the predicted risk level.

🚀 Technologies used
Python

pandas

scikit-learn

imbalanced-learn (SMOTE)

Streamlit (for the user interface)

🧪 Example Use Case
An HR manager can input employee data into the app (either manually or by uploading a file) and receive a predicted risk level. Based on that, the company can take preventive steps such as offering training, conducting reviews, or improving job satisfaction.

