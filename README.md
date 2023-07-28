# -Detecting-RPL-Attacks-with-ML-
Comparison of Machine Learning Algorithms to Detect RPL-Attacks 
"Comparison of Machine Learning Algorithms to Detect RPL-Attacks ".

Detecting RPL Attacks
1. Introduction
The purpose of this project is to develop a system for detecting RPL attacks using machine learning algorithms. The dataset used for training and testing consists of various features extracted from network traffic. The project aims to evaluate the performance of different classifiers in detecting RPL attacks and measure their accuracy rates.

Making data meaningful
Data Preprocessing
The project starts with loading the dataset using the Pandas library. The dataset is divided into input features (X) and the target variable (y). The input features are then split into training and testing sets using the train_test_split function from the sklearn library. The data is normalized using the StandardScaler to ensure all features are on a similar scale.

Basic Model 
o	Logistic Regression
The logistic regression classifier is applied to the preprocessed data. The training time and accuracy rate are calculated using the training set. The trained model is then used to predict the target variable for the testing set. The confusion matrix is generated, and the accuracy rate is calculated based on the predicted and actual values.
o	Random Forest Classification
The random forest classifier is employed to classify the data. Similar to logistic regression, the training time and accuracy rate are calculated. The model is used to predict the target variable for the testing set, and the accuracy rate is determined using the confusion matrix.

o	Decision Tree Classifier
The decision tree classifier is utilized for classification purposes. The training time and accuracy rate are computed, and the model is used to predict the target variable for the testing set. The accuracy rate is calculated based on the confusion matrix.

o	Naive Bayes Classifier
The naive Bayes classifier is applied to the preprocessed data. The training time and accuracy rate are determined, and the model is used to predict the target variable for the testing set. The accuracy rate is calculated using the confusion matrix.

o	K-Nearest Neighbors (KNN) Classifier
The KNN classifier is employed to classify the data. The training time and accuracy rate are computed, and the model is used to predict the target variable for the testing set. The accuracy rate is calculated based on the confusion matrix.


o	 Results and Analysis
After applying the various classifiers to the dataset, the accuracy rates and training times are collected and analyzed. The results show the performance of each classifier in detecting RPL attacks. Based on the accuracy rates, it can be observed that the random forest achieved the highest accuracy rate, followed by the Decision tree. However, the naïve byer had the fastest training time compared to other classifiers.
  
o	Conclusion
In conclusion, this project aimed to detect RPL attacks using machine learning algorithms. The performance of different classifiers was evaluated in terms of accuracy rate and training time. The results indicate that random forest performed the best in terms of accuracy rate, while naive bayes had the fastest training time. Further optimizations and fine-tuning of the classifiers can potentially improve the detection accuracy and reduce training time. Overall, this project demonstrates the potential of machine learning in detecting RPL attacks and provides insights for further research in this area.

