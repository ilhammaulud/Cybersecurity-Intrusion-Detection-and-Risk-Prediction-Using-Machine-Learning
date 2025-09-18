# Cybersecurity Intrusion Detection and Risk Prediction Using Machine Learning

## Repository Outline

1. README.md - Project overview explanation
2. P1M2_Ilham_Maulud.ipynb - Notebook containing data processing with Python
3. P1M2_Ilham_Maulud_inf.ipynb - Notebook containing model experiments with inference data
4. url.txt - Contains the Streamlit link
5. dataset.csv - Contains the dataset used
6. deployment folder - Contains files used for deployment
7. XGBoost_best_model. joblib - Saved Model


## Problem Background
In today's digital age, cyberattacks have become a serious threat to the security of organizational data and networks. Many systems still rely on traditional detection methods that are less effective at recognizing new attack patterns. This project aims to build a cyber intrusion risk prediction model using network transaction data, enabling the automatic and accurate identification of potential attacks. With this model, organizations can enhance network security and reduce losses from cyber incidents.

## Project Output
This project produces a machine learning model for detecting cyber intrusion risks. This model is capable of classifying network activities as safe or risky with high accuracy after undergoing preprocessing, scaling, and hyperparameter tuning. Other outputs of this project include a model performance evaluation report (precision, recall, f1-score, and accuracy) and recommendations for mitigation strategies based on prediction results.

## Data
The data used comes from the Cybersecurity Intrusion Detection dataset, which contains network activity information for detecting cyberattacks. This dataset has 10 feature columns that include numerical and categorical information such as session_id, network_packet_size, protocol_type, login_attempts, and others. The dataset consists of 9,537 rows and 10 columns, with some categorical features handled using One-Hot Encoding and numerical features scaled to improve model performance. Overall, the data is ready to be used for training and evaluating the intrusion risk classification model.

## Method
The method used in this project is Supervised Learning for classifying cyber intrusion risk. The process includes data preprocessing, which involves handling numerical columns with scaling and categorical columns with One-Hot Encoding, to prepare the data for input into the model. Several classification algorithms were tested, including Decision Tree, Random Forest, Gradient Boosting, KNN, SVM, and XGBoost. The models were evaluated using Cross Validation to obtain the average accuracy and standard deviation, allowing the best model to be selected before hyperparameter tuning was performed.

## Stacks
This project uses the Python programming language with several key libraries and tools for data analysis and machine learning, including:

1. Pandas and NumPy: data manipulation and numerical computation.

2. Scikit-Learn: data preprocessing, pipelines, machine learning models, evaluation, and cross-validation.

3. XGBoost: implementation of a boosting model for classification.

4. Matplotlib, Seaborn, and Plotly: data visualization and analysis results.

5. Streamlit: building interactive web applications to display model results and dashboards.

Additionally, this project also utilizes pipelines and ColumnTransformer to simplify preprocessing and integration with various machine learning models.

## Reference
Here are some supporting references and links used in this project:

Dataset Cybersecurity Intrusion Detection: https://www.kaggle.com/datasets/dnkumars/cybersecurity-intrusion-detection-dataset

Streamlit: https://docs.streamlit.io/

Scikit-Learn: https://scikit-learn.org/stable/documentation.html

XGBoost Documentation: https://xgboost.readthedocs.io/

Reference visualization and dashboard: Plotly https://plotly.com/python/
