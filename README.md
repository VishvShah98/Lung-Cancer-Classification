# Lung Cancer Classification Analysis Using kNN, SVM and ANN

## Abstract
This research project focuses on the analysis of lung cancer classification using k-nearest neighbor (kNN), Support Vector Machine (SVM), and Artificial Neural Network (ANN) algorithms. The study utilizes the NCCTG database for lung cancer data and employs Genetic Algorithm (GA) and Principal Component Analysis (PCA) for feature reduction. The goal is to develop an accurate classification model for lung cancer detection.

## Introduction
Lung cancer is a serious health issue that requires early detection for effective treatment. This research aims to create classifiers using kNN, SVM, and ANN algorithms to classify lung cancer cases. By analyzing a dataset from the NCCTG database, this study provides insights into the effectiveness of these algorithms for early diagnosis and prognosis.

## Methodology
The study involves the following steps:

1. **Database:** The lung cancer dataset from the NCCTG database is used, containing 23 features and labels categorized as 'Low', 'Medium', and 'High'.

2. **Genetic Algorithm (GA):** GA is employed for feature reduction. Random sets of features are generated as an initial population. GA uses selection, crossover, and mutation operations to evolve the population over iterations. Logistic Regression is used as the fitness function to evaluate the accuracy of each chromosome.

3. **k Nearest Neighbors (kNN) Algorithm:** The kNN algorithm classifies data points based on the distance to their k nearest neighbors. The algorithm is applied to the dataset, and the optimal value of k is determined empirically.

4. **Support Vector Machine (SVM):** SVM is a supervised learning method used for classification. It aims to find an optimal hyperplane for data separation. SVM is utilized to classify lung cancer cases.

5. **Artificial Neural Network (ANN):** ANN is a learning algorithm inspired by biological neural networks. It consists of input, hidden, and output layers connected by weighted connections. ANN is trained using the dataset to predict lung cancer cases.

6. **Proposed Approach:** The kNN, SVM, and ANN algorithms are applied to the original dataset. Feature reduction using GA is performed in two rounds. The reduced features are used as input for GA in the second round to further reduce the feature set.

## Results
The study shows that kNN, SVM, and ANN algorithms perform exceptionally well on the original dataset, achieving 100% accuracy. Through feature reduction using GA, the number of features is reduced while maintaining high accuracy. The optimal trade-off between accuracy and the number of features is achieved in round 2, where kNN achieves 99% accuracy with 5 selected features.

## Conclusion
The study concludes that kNN, SVM, and ANN algorithms are effective for lung cancer classification. The use of Genetic Algorithm for feature reduction enhances the performance of these algorithms. The results highlight the potential of developing a prognosis tool for lung cancer screening based on this approach.

## Future Work
Future work can involve the development of a prognosis tool for lung cancer screening using the insights from this study. Additionally, exploring other feature reduction techniques such as PCA and LDA, and experimenting with different fitness functions for GA can further enhance the accuracy and efficiency of the classification model.
