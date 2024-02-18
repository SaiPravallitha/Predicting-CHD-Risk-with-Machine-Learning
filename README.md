# Predicting-CHD-Risk-with-Machine-Learning
## Data Science Project
### Introduction
Coronary Heart Disease (CHD) poses a significant health risk, often associated with poor lifestyle choices. This project leverages data from an ongoing cardiovascular study in Framingham, Massachusetts, available on Kaggle, to predict the 10-year risk of future CHD. The study aims to identify key health factors linked to CHD and assess the accuracy of various classification models, including logistic regression, decision trees, random forests, and support vector machines.

### Business Problem
The primary objective is to determine the key health factors strongly associated with CHD and identify the most accurate classification model for predicting the 10-year risk. The project seeks to assist the healthcare system in early identification of patients at risk for CHD, enabling timely intervention or preventive measures.

### Data Source and Description
The dataset, obtained from Kaggle [check it here](https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression?resource=download), encompasses the health history of 4,000 residents in Framingham. Fifteen attributes are categorized into four groups. Models used for analysis include logistic regression, decision trees, random forests, support vector machines, and principal component analysis (PCA).

### Challenges Faced
 - Unbalanced Data:
     - Addressing the imbalance (15% with CHD risk, 85% without) requires techniques like data resampling or ensemble learning.
 - Biased Dataset:
     - Biases in data collection can lead to inaccurate models; identifying and mitigating these biases is crucial.
 - Feature Selection:
     - Selecting relevant features is challenging, requiring careful consideration to avoid overfitting or underfitting.
 - Low Correlation:
     - Combining supervised and unsupervised models, such as PCA, helps overcome low correlation and multicollinearity issues.
 - Understanding Data Nature:
Used Combination of Models:
Combining supervised (logistic regression, decision tree, random forest, SVM) and unsupervised (PCA) models helps extract insights from low-correlation data.
Balancing Data:
Employing oversampling and undersampling techniques ensures a balanced dataset for accurate model training.
Data Preprocessing:
Data Cleaning:
Addressing null values using R code ensures a complete and error-free dataset.
Nature of Independent Variables:
Analyzing independent variables' normal distribution aids in understanding underlying patterns and relationships.
Model Building:
PCA:
Using PCA to reduce dimensionality, extract important features, and address multicollinearity.
Logistic Regression, Decision Trees, Random Forests, SVM:
Employing these models with undersampling and feature sampling techniques for improved accuracy.
Results and Analysis:
Random Forest outperformed other models in terms of sensitivity, recall, and precision, especially after feature selection and balancing techniques. The study concludes that Random Forest, when applied to undersampled data, is the most effective model for predicting CHD risk.

Conclusion:
This project highlights the significance of machine learning in predicting CHD risk, showcasing the Random Forest model's superiority. Early identification through accurate prediction models can significantly impact patient outcomes and alleviate the burden on the healthcare system. The results and methodologies are documented to contribute to future research and inform decision-making in similar contexts.

For detailed insights and code implementation, refer to the project on Kaggle here.
