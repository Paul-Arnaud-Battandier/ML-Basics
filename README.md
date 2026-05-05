# Corporate Default Prediction - Machine Learning Benchmark

This project focuses on predicting corporate bankruptcy using a dataset of sixty explanatory variables and one binary target. The primary objective is to evaluate and compare the efficacy of diverse classification algorithms to achieve the highest possible predictive accuracy.

## Project Scope

The implementation follows a structured operational workflow designed to maximize model performance:

*   **Model Benchmarking**: Comparative analysis of standard classifiers against advanced gradient boosting techniques.
*   **Feature Engineering**: Rigorous selection of the most relevant variables to reduce test error and improve generalization.
*   **Hyperparameter Optimization**: Systematic tuning of model configurations to find the ideal balance for prediction.
*   **Final Evaluation**: Comprehensive diagnostic of the top performing model based on the weighted F1 score.

## Repository Structure

| File / Directory | Technical Purpose |
| :--- | :--- |
| `0Bankruptcy_T.csv` | Primary dataset containing financial indicators and the binary target variable |
| `Comparaison_Modeles.xlsx` | Detailed spreadsheet summarizing performance metrics across all tested algorithms |
| `MachineLearning.ipynb` | Comprehensive research notebook including data cleaning and model training |

## Algorithms and Methodology

The project implements a wide range of machine learning models to identify the most robust solution:

*   **Standard Models**: Logistics Regression, K Nearest Neighbors, Random Forest, SVM, and Neural Networks.
*   **Advanced Model**: XGBoost was integrated for its high efficiency in handling complex tabular data classification.
*   **Metrics Framework**: Accuracy is measured alongside Precision, Recall, Weighted F1 score, and Computation Time.
*   **Final Diagnostics**: The selected model undergoes ROC Curve analysis to identify specific limitations and strengths.

## Technical Stack

*   **Data Manipulation**: Pandas and NumPy for robust dataset handling.
*   **Modeling**: Scikit Learn for standard algorithms and XGBoost for advanced boosting.
*   **Visualization**: Matplotlib and Seaborn for performance and feature importance analysis.

## Conclusion

The benchmark confirms that systematic variable selection combined with hyperparameter tuning significantly enhances prediction rates. The final results highlight how gradient boosting often outperforms traditional linear models when dealing with high dimensional financial data.
