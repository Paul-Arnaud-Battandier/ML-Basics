🏦 Corporate Default Prediction: A Machine Learning BenchmarkThis project aims to predict corporate default using a dataset containing 60 explanatory variables and one binary target variable. The objective is to achieve the best possible prediction rate while comparing several classification algorithms.

🎯 Project ScopeThe project is divided into four main operational stages:Model Benchmarking: Comparing the performance of five standard algorithms plus an advanced model (XGBoost) .Feature Engineering: Selecting the most relevant variables to reduce test error.Hyperparameter Optimization: Tuning models to find the ideal configuration for prediction.Final Evaluation: Deep-dive analysis of the most performing model based on the weighted F1-score.

🤖 Algorithms ImplementedThe following models were implemented and compared using the same set of explanatory variables:Logistic Regression K-Nearest Neighbors (KNN) Random Forest Support Vector Machine (SVM) Neural Networks Advanced Model: XGBoost (Chosen for its high efficiency in tabular data classification).

📊 Evaluation MetricsEach model was evaluated according to:Precision & Recall Weighted F1-score Classification Accuracy Rate Computation Time 

🛠️ Methodology & OptimizationFeature SelectionFor the selected model, a rigorous variable selection process was conducted to observe how the test error evolves with different feature subsets .Hyperparameter TuningTwo specific models underwent hyperparameter optimization to maximize performance and minimize overfitting.Final Model AnalysisThe model with the highest weighted F1-score (typically XGBoost) was selected for a final diagnostic, including:ROC Curve analysis.Identification of model limitations and weaknesses.

📁 Repository StructurePlaintext.

├── Nom1_Nom2_Nom3_code.ipynb    # Fully commented Google Colab Notebook

├── Nom1_Nom2_Nom3_projet.pdf    # 2-page summary note + 3-page appendix

├── data/                        # Dataset folder

└── README.md                    # Project documentation

⚙️ RequirementsTo run the code provided in the notebook, the following Python libraries are required:pandas, numpy (Data manipulation)scikit-learn (Standard ML models & metrics)xgboost (Advanced Gradient Boosting)matplotlib, seaborn (Visualization)
