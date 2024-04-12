# Cross-Validation Best Practices: Avoiding Data Leakage

## Project Overview

This project aims to demonstrate the correct application of cross-validation techniques in machine learning models, specifically focusing on how to prevent data leakage during model training. The primary focus is on handling imbalanced datasets using various sampling techniques and evaluating model performance with different machine learning algorithms.

### Objectives

- **Implement Sampling Techniques**: Apply undersampling and oversampling correctly to balance the dataset.
- **Model Training**: Train various models using the balanced datasets to identify the best performer.
- **Evaluation**: Assess model performance using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC curves.
- **Best Practices**: Showcase the importance of proper cross-validation techniques to avoid data leakage and overfitting.

### Methods Used

- **Near Miss UnderSampling and SMOTE OverSampling**: Techniques used to balance the class distribution in the dataset. Near Miss focuses on reducing the majority class by selecting samples closest to the minority class boundary, while SMOTE generates synthetic samples from the minority class.
- **Cross-Validation**: Integrated into the model training process to ensure the model's ability to generalize to new, unseen data.
- **Performance Metrics**: Accuracy, precision, recall, F1 score, and AUC-ROC are used for model evaluation.


### Models Evaluated

- **Logistic Regression**
- **K-Nearest Neighbors**
- **Support Vector Machine**
- **Random Forest Classifier**

### Results

The models were rigorously tested with cross-validation methods integrated within their training process. Performance metrics were critically analyzed to compare the efficacy and robustness of each model under study. The ROC curves were used to visualize performance and highlight the impact of proper sampling and validation strategies.

### Conclusions

The project underlines the critical importance of correct data handling, balancing techniques, and cross-validation in building predictive models for imbalanced datasets. It also provides insights into the selection of appropriate models and techniques to optimize performance and ensure reliable predictions.

