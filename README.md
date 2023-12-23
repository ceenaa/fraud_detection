# Fraud Detection
Credit Card fraud detection based on [Kaggle dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Applied and tested with Clustering, Logistic Regression, Random Forest, and XG BOOST, along with some sampling techniques for balancing the data.

## Some Tips
* Features V1 to V28 are the principal components obtained with PCA, so they are scaled. Only time and amount need to be scaled.
* The F1-score is a great scoring metric for imbalanced data when more attention is needed on the positives, making it suitable for measuring model performance.
* The dataset is highly imbalanced, and it is important to take care of overfitting on the Non-Fraud class. The main techniques used were Random Under-sampling and SMOTE for oversampling the minority class.
* Secondly, be aware that Fraud transactions can be natural outliers compared to Non-Fraud transactions. Be careful about Anomaly detection, especially outlier removal.
* Be careful about splitting test and train data before applying any sampling techniques. Only apply sampling techniques to the train data.
* At the end, be cautious about sampling and cross-validation; if not applied correctly, it can cause data leakage.

# Clustering with Kmeans

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/253881ed-e2cb-4f1c-aaa2-ac6fd172bae8)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/ef9c6631-c7ca-4880-9c16-2249e3e35368)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/8c99b5a2-510a-48e3-bbce-73024425a351)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/adb15220-3a6e-4135-b9a3-f1e764940ad2)

# Logistic Regression with Random Under Sampling

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/c930ca5e-8060-4de3-8819-229df4da1aa2)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/4ff17071-e694-4448-8475-1329b63452ac)

# Logistic Regression with SMOTE for Oversampling

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/9cb3e33a-4db1-4536-a270-6ca192f78907)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/f85b58ca-ec08-4a08-b3d1-8fed15f1d2ef)

# Random Forest with SMOTE

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/896428fa-3757-499d-922e-e5a3d24de5d3)

![image](https://github.com/ceenaa/fraud_detection/assets/88087819/7f669a45-4a94-42c4-be73-a99c19e2f16a)

# XG BOOST
![image](https://github.com/ceenaa/fraud_detection/assets/88087819/21811af9-b48b-4cf8-8df0-df829f4f5107)
![image](https://github.com/ceenaa/fraud_detection/assets/88087819/16d23dcd-fc54-449d-b244-a3cabe270a3f)
