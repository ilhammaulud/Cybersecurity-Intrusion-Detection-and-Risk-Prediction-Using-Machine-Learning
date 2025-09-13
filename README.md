# Cybersecurity Intrusion Detection and Risk Prediction Using Machine Learning

## Repository Outline

1. README.md – General project overview
2. P1M2_Ilham_Maulud.ipynb – Notebook for data processing with Python
3. P1M2_Ilham_Maulud_inf.ipynb – Notebook for model testing with inference data
4. url.txt – Contains Streamlit deployment link
5. dataset.csv – Dataset used in the project
6. deployment folder – Files for deployment setup
7. XGBoost_best_model.joblib – Saved best-performing model


## Problem Background
In today’s digital era, cyberattacks pose serious threats to organizational data and network security. Many systems still rely on traditional detection methods that struggle to identify new attack patterns. This project aims to build a machine learning model for predicting cybersecurity intrusion risks using network transaction data, enabling automatic and accurate detection of potential attacks. With this model, organizations can strengthen network security and minimize losses from cyber incidents.

## Project Output
This project delivers a machine learning model for intrusion risk detection. The model classifies network activities as safe or risky with high accuracy after preprocessing, scaling, and hyperparameter tuning. Additional outputs include performance evaluation reports (precision, recall, f1-score, and accuracy) as well as mitigation strategy recommendations based on prediction results.

## Data
The dataset used is the Cybersecurity Intrusion Detection Dataset, which records network activities to detect cyberattacks. It contains 9,537 rows and 10 features, including both categorical and numerical attributes such as session_id, network_packet_size, protocol_type, login_attempts, and more.

- Categorical features were transformed using One-Hot Encoding.
- Numerical features were scaled to improve model performance.

The dataset is fully prepared for training and evaluating classification models.

## Method
This project applies Supervised Learning for intrusion risk classification. The process includes:

1. Preprocessing: scaling numeric features and encoding categorical ones.
2. Modeling: testing several algorithms such as Decision Tree, Random Forest, Gradient Boosting, KNN, SVM, and XGBoost.
3. Evaluation: models were assessed using cross-validation to compute average accuracy and standard deviation, ensuring robust model selection before hyperparameter tuning.

## Stacks
The project uses Python with essential libraries and tools for data analysis and machine learning, including:

1. Pandas & NumPy – Data manipulation and numerical computations
2. Scikit-Learn – Preprocessing, pipelines, ML models, evaluation, and cross-validation
3. XGBoost – Boosting-based classification model
4. Matplotlib, Seaborn, Plotly – Data visualization and analytical charts
5. Streamlit – Interactive web app for model deployment and dashboards

Additionally, pipelines and ColumnTransformer were applied to streamline preprocessing and integration across multiple models.

## Reference

- Dataset Cybersecurity Intrusion Detection: https://www.kaggle.com/datasets/dnkumars/cybersecurity-intrusion-detection-dataset
- Dokumentasi Streamlit (untuk deployment aplikasi web interaktif): https://docs.streamlit.io/
- Dokumentasi Scikit-Learn (untuk machine learning & preprocessing): https://scikit-learn.org/stable/documentation.html
- XGBoost Documentation: https://xgboost.readthedocs.io/
- Dashboard Plotly: https://plotly.com/python/
- [Basic Writing and Syntax on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [readme](https://github.com/fahmimnalfrzki/Swift-XRT-Automation)
- [Another example](https://github.com/sanggusti/final_bangkit)
- [Additional reference](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)


