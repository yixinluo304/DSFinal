# ML-Project

# Key Takeaways

- The dataset examines diabetes indicators.
- It includes an extensive set of feature variables.
- Both statistical and machine learning analyses have been conducted.

## Summary

The dataset under analysis is designed to highlight the correlation between lifestyle and diabetes within the US population. The **CDC Diabetes Health Indicators** dataset is a compilation of healthcare statistics and lifestyle survey information. It contains 253,680 instances, each with 21 distinct features, encompassing demographics, lab test results, and survey responses.

### Feature Engineering Process

The process of feature engineering entails:

- Extraction of features and target variables from the dataset.
- Utilization of techniques like oversampling to balance the dataset for the positive class labeled 'Diabetes_binary'.
- Creation of visual representations such as count plots and histograms to gain a better understanding of feature distributions.

### Exploratory Data Analysis and Feature Engineering

Following the initial feature engineering phase, the dataset has been subjected to:

- Regression analysis, with the application of various statistical tests such as t-tests, F-tests, and confidence interval analyses. These tests gauge the impact of features relative to the target variable, which consist of diabetes, pre-diabetes, or no diabetes classifications.
- The analyses offer vital insights, pinpointing the significance of features such as BMI, Education, Age, Income, and General Health (GenHlth) in predicting diabetes presence.
- These insights have been leveraged to develop a logistic regression model and calculate performance indicators like the ROC curves and AUC scores.

### Classification Model Applications

Concurrently, classification tasks have been performed using methods such as:

- Logistic Regression,
- Decision Trees, 
- k-Nearest Neighbors (KNN),
- Gaussian Naive Bayes.
- Multi-layer Perceptron Classifier(MLP)

These methods have been evaluated on criteria like accuracy, confusion matrices, and ROC-AUC scores. The critical evaluation metrics, including recall, precision, and F1 score, reflect the predictive accuracy and dependability of the various models implemented.

### Conclusion 
 Based on the k-fold cross validation of the models the MLP model gave the best reults for the cv scores : 0.76100672, making it the best model amongst the all.