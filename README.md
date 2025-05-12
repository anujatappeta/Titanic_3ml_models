# Titanic Dataset Prediction Models

## Overview
This project focuses on predicting Titanic survivors using machine learning models: Logistic Regression, Random Forest, and XGBoost. The goal is to analyze the Titanic dataset and apply various predictive models to identify which passengers survived.

## Tools & Libraries Used
- **Python** (Google Colab)
- **Libraries**: pandas, numpy, seaborn, sklearn, xgboost


## Steps Involved
1. **Data Preprocessing**: 
   - Loaded and cleaned the Titanic dataset.
   - Handled missing values and categorical data using One-Hot Encoding.
   
2. **Model Training**:
   - Implemented Logistic Regression, Random Forest, and XGBoost classifiers.
   - Evaluated model performance using accuracy, precision, recall, and F1-score.

3. **Results**:
   - **Logistic Regression**: Best overall performance with 82.5% accuracy.
   - **Random Forest**: 80.4% accuracy, slightly behind Logistic Regression.
   - **XGBoost**: 74.8% accuracy, struggled more with predicting survivors.

## Key Insights
- Logistic Regression performed the best in terms of accuracy and balanced precision and recall for both classes.
- Random Forest showed strong performance but was slightly behind Logistic Regression.
- XGBoost showed the lowest performance, particularly in predicting survivors.

## Credits
Special thanks to [**Dhanush Polasi**](https://github.com/DhanushP545) for the original Titanic EDA and Survival Prediction project. I used his repository as a reference to understand the foundational concepts and to develop my own Titanic survivor prediction models.

## How to Run
1. Clone or download the repository.
2. Open the notebook in Google Colab or Jupyter.
3. Run the cells in order to preprocess the data, train the models, and evaluate performance.

## License
This project is open for learning and sharing. Give credit if you reuse or build upon it.
