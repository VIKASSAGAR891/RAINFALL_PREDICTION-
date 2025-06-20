_🌦️ Rainfall Prediction using Machine Learning_ 

This project aims to predict whether rainfall will occur based on various weather conditions like temperature, humidity, cloud cover, wind, and atmospheric pressure. The project uses a Random Forest Classifier to build a binary classification model and includes complete steps from data preprocessing to model deployment.

The goal of this project is to develop a machine learning model that predicts whether it will rain or not based on historical weather data. The model takes features like pressure, temperature, dewpoint, humidity, cloud cover, sunshine duration, wind direction, and wind speed as input.

->Technologies Used
Python
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Visualization
Scikit-learn – Model training, evaluation, hyperparameter tuning
Pickle – Model serialization


->EDA (Exploratory Data Analysis)
Univariate distribution plots for each feature
Boxplots to identify outliers
Correlation heatmap to study feature relationships
Rainfall class distribution visualization


->Data Preprocessing
Removed unnecessary columns (day, redundant temperature features)
Handled missing values using mode (for categorical) and median (for numerical)
Converted categorical labels to numerical values (yes → 1, no → 0)
Addressed class imbalance using downsampling


->Modeling
Model: Random Forest Classifier
Performed hyperparameter tuning using GridSearchCV
Parameters tuned: n_estimators, max_depth, min_samples_split, min_samples_leaf, max_features
Cross-validation used to validate model robustness


->Evaluation
Evaluated on both training and testing sets using:
Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
Cross-validation scores


->Model Deployment  
Trained model saved using pickle in .pkl format
Model can be loaded anytime to predict rainfall based on new unseen input data

