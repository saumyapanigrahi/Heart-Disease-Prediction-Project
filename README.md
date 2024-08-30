# Heart Disease Prediction Using Machine Learning

This repository contains my recent project where I applied various machine learning techniques to predict heart disease based on clinical and demographic data. The goal of this project was to explore the effectiveness of different models in identifying potential heart disease in patients, using a dataset sourced from the Cleveland Clinic Foundation.

Project Overview:
Dataset: The dataset comprises 303 patient records with 14 features, including age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, electrocardiographic results, maximum heart rate achieved, exercise-induced angina, and other diagnostic indicators. The target variable indicates the presence (1) or absence (0) of heart disease.

Data Analysis:

Performed extensive exploratory data analysis (EDA) to understand feature distributions, correlations, and identify any missing values.
Visualized key features using histograms, bar plots, and heatmaps to detect potential patterns and correlations with the target variable.
Model Building:

Implemented multiple machine learning algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest Classifier using scikit-learn.
Utilized cross-validation techniques and hyperparameter tuning (Grid Search and Randomized Search) to enhance model performance and avoid overfitting.
Model Evaluation:

Evaluated models using various metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
The Random Forest Classifier achieved the highest accuracy and balanced performance across all metrics, making it the most effective model for this dataset.
How to Run the Code:
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/heart-disease-prediction.git
Navigate to the project directory and install the required packages:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook to reproduce the analysis and results.
Key Files in This Repository:
heart_disease.csv: The dataset used for analysis.
Heart_Disease_Prediction_Using_Machine_Learning.ipynb: Jupyter Notebook containing all the code for data analysis, model training, and evaluation.
requirements.txt: List of Python libraries required to run the code.
Future Work:
Explore advanced algorithms such as Gradient Boosting Machines or Deep Learning models.
Implement feature engineering techniques to enhance model performance further.
Contributing:
Feel free to fork this repository, make enhancements, and submit pull requests. All suggestions are welcome!
