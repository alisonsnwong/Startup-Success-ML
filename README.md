# Startup Sucess with Optimizing Machine Learning Algorithms

This study aims to identify the most accurate algorithm for predicting the success of startups. Four commonly used algorithms, namely logistic regression, decision tree, support vector machine (SVM), and K-nearest neighbors (KNN), were evaluated and compared in terms of their predictive performance. The evaluation results revealed that the logistic regression algorithm exhibited the highest accuracy among the tested models with the second-highest computational time. The SVM algorithm demonstrated the fastest computational time but with the lowest accuracy of 69.27%. These findings contribute to the understanding of the strengths and limitations of various algorithms in predicting startup success. Future research could focus on optimizing the computational efficiency of the decision tree algorithm, as it has the slowest computational time of 23.49 seconds, or exploring hybrid models that combine the strengths of different algorithms.

:robot: **Tools & Libraries**: Python, Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn (for comparison)

:robot: **Data Source**: Provided by an ML engineer from GMO. It contains 923 startup companies and 49 features.

### Data Preprocessing:
* Dropped unnecessary columns
* Replaced NA values with feature averages
* Standardized features to have zero mean and unit variance
  
### Feature Importance:
Features such as **relationships** and **milestones** were found to be significant predictors of startup success. A correlation heatmap was used to determine the importance of each feature.

### Four machine learning algorithms were implemented and evaluated:
**Logistic Regression**: Used gradient descent to update weights and biases. Achieved the highest accuracy (75.68%) with a computational time of 0.034 seconds.

**Decision Tree**: Implemented using attribute selection measures like entropy, Gini impurity, and information gain. Achieved an accuracy of 72.43% but with the slowest computational time (23.49 seconds).

**K-Nearest Neighbors (KNN)**: Evaluated different distance metrics and determined the optimal number of neighbors (K). Achieved an accuracy of 74.05% with a computational time of 0.077 seconds.

**Support Vector Machine (SVM)**: Used iterative gradient descent method. Achieved the lowest accuracy (69.27%) but had a competitive computational time (0.022 seconds).
