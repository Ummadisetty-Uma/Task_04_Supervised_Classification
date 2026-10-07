Supervised Classification Modeling & Tuning
Project Overview
This project focuses on training, tuning, and comparing multiple supervised classification algorithms.
The objective is to identify the best-performing classification model based on validation performance.
Models Used
Four different classification architectures were trained and evaluated:
•	Logistic Regression
•	Random Forest
•	XGBoost
•	LightGBM
Methodology
The project includes:
•	Data preprocessing
•	Train-test splitting
•	Stratified K-Fold cross-validation
•	Baseline model training
•	Hyperparameter optimization using GridSearchCV
•	Model evaluation
•	Champion model selection
•	Model serialization
Evaluation Metrics
The models were evaluated using:
•	Precision
•	Recall
•	F1-Score
•	ROC-AUC
•	Confusion Matrix
•	ROC-AUC Curves
Model Comparison
Model	Precision	Recall	F1-Score	ROC-AUC
XGBoost	0.7926	0.6728	0.7278	0.9314
LightGBM	0.7844	0.6684	0.7218	0.9293
Random Forest	0.7947	0.6148	0.6933	0.9208
Logistic Regression	0.7406	0.6173	0.6734	0.9078
Champion Model
Based on ROC-AUC validation performance, XGBoost was selected as the champion model with an ROC-AUC of 0.9314.
The trained champion pipeline was serialized using the .joblib format so that it can be reused for future predictions without manually repeating the preprocessing and model-training steps.
Project Deliverables
•	Jupyter Notebook containing the complete implementation
•	Model comparison table
•	ROC-AUC curves
•	Confusion matrices
•	Hyperparameter tuning results
•	Serialized champion model (.joblib)
•	CSV model comparison file
Technologies Used
•	Python
•	Pandas
•	NumPy
•	Scikit-learn
•	XGBoost
•	LightGBM
•	Matplotlib
•	Seaborn
•	Joblib
•	Jupyter Notebook

