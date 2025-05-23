# Diabetes Prediction System using SVM Classifier

This project presents a machine learning–based system for predicting the likelihood of diabetes in patients based on key medical attributes. It utilizes a Support Vector Machine (SVM) classifier trained on a structured dataset to determine whether an individual is at risk of developing diabetes. The goal of this project is to support early diagnosis, improve patient awareness, and enable timely medical intervention through the use of predictive analytics.

Diabetes is one of the most prevalent chronic diseases globally, often going undetected until it reaches an advanced stage. Many individuals are unaware of their condition due to the subtle nature of early symptoms. By using a data-driven approach, this system offers a tool that can analyze various health indicators and output a reliable prediction to assist both patients and healthcare professionals in decision-making.

The dataset used in this project is derived from a publicly available medical record source (such as the Pima Indians Diabetes Dataset). It includes features such as glucose level, insulin, BMI, age, number of pregnancies, blood pressure, and more. These inputs are preprocessed by handling missing values, standardizing data, and performing feature scaling to improve the performance of the SVM model.

The model is built using a Support Vector Machine classifier, which is well-suited for binary classification tasks such as diabetes prediction. The SVM algorithm identifies the optimal hyperplane that separates diabetic and non-diabetic cases in the feature space. The model is trained and validated using a portion of the dataset, and performance is evaluated using accuracy, precision, recall, and confusion matrix.

To improve usability, a simple and clean user interface is built using Streamlit. Users can input their health parameters through sliders and input fields, and the system instantly predicts the likelihood of diabetes. The interface displays a clear diagnostic message and can optionally provide insights into which features had the most impact on the prediction.

Looking forward, the project can be enhanced by integrating more patient data from diverse populations, experimenting with other classification algorithms (like Random Forest or XGBoost), and incorporating explainability features to show users how the prediction was made. Future versions could also include integration with electronic health record systems or be deployed as a mobile app for personal health monitoring.

This project was developed as part of an academic exploration into the intersection of healthcare and machine learning. It aims to demonstrate how classical machine learning models like SVMs can be effectively used in real-world medical prediction tasks when paired with proper data preprocessing and deployment techniques.
