# Diabetes Detection Using Deep Learning



##### **Overview**



This project implements a diabetes risk prediction system using the Framingham Heart Study dataset (4,240 records, 16 features). The objective is to develop a high-accuracy classification model and enhance transparency using Explainable AI (XAI).





Dataset



* Source: Framingham Heart Study
* Records: 4,240
* Features: 16 clinical and demographic variables
* Target: Binary diabetes outcome



Key features include age, BMI, systolic/diastolic blood pressure, cholesterol levels, glucose, smoking habits, and medical history indicators.





Data Preprocessing



* Removed duplicate records
* Handled missing values using imputation
* Performed feature selection to retain relevant predictors
* Applied feature scaling (normalization)
* Split dataset into 80% training and 20% testing







Models Implemented



Traditional ML models:



* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Gaussian Naive Bayes



Deep Learning model:



Artificial Neural Network (TensorFlow)



* Input layer matching feature count
* Hidden layers with ReLU activation
* Binary classification output layer





Evaluation Metrics



* Accuracy
* Confusion Matrix
* Precision and Recall



The neural network achieved **88.34%** accuracy, outperforming traditional machine learning models.





Explainable AI (XAI)



SHAP (SHapley Additive Explanations) was integrated to:



* Quantify feature contributions
* Provide local and global interpretability
* Improve transparency for clinical decision support





Tech Stack



Python, Pandas, NumPy, Scikit-learn, TensorFlow, Matplotlib, Seaborn, SHAP





Outcome



The project demonstrates the effectiveness of combining deep learning with interpretability techniques to build reliable and transparent healthcare prediction systems.



