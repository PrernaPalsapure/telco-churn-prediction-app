# telco-churn-prediction-app

This project predicts whether a telecom customer is likely to churn or stay using machine learning techniques. Built using Python, Streamlit, and Logistic Regression with PCA, the app takes real-time user input and provides a churn prediction on the spot.

1) My_Churn.ipynb	                     : Full Jupyter notebook with EDA, preprocessing, PCA, model training & evaluation

2) WA_Fn-UseC_-Telco-Customer-Churn.csv : Original Telco dataset used for training

3) Telco_Churn_Project_Summary.pptx	   : A summarized presentation of project workflow and insights

4) churn_video-ezgif.com-speed.gif	     : Demo GIF showcasing the working Streamlit app

 Features :

✅ Clean, interactive Streamlit web interface

✅ Predicts if a customer will churn or stay

✅ Uses Logistic Regression with Principal Component Analysis (PCA)

✅ Handles all categorical and numerical features dynamically

✅ Converts SeniorCitizen from numeric to Yes/No

✅ Easy to deploy and extend

 Technologies Used :

1) Python
2) Pandas, NumPy, Scikit-learn
3) PCA (Dimensionality Reduction)
4) Streamlit
5) Matplotlib / Seaborn for EDA
6) Jupyter Notebook
7) GitHub for version control & sharing

 Model Insights :

The Logistic Regression model was trained after applying PCA to reduce dimensionality and improve performance.
The features used include service types, contract length, charges, and customer demographics.
The app excludes customerID to focus only on predictive features.
