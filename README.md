# Task 6: K-Nearest Neighbors (KNN) Classification

## 🔍 Objective
To implement and understand the KNN algorithm for classification using the Iris dataset.

## 🛠 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📊 Dataset
*Iris Dataset*  
[Click here to download](https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv)

## 📌 Steps Followed
1. Loaded and explored the Iris dataset.
2. Encoded categorical labels into numeric.
3. Normalized features using StandardScaler.
4. Split dataset into training and testing sets.
5. Trained a KNN classifier using KNeighborsClassifier from sklearn.
6. Tested with different values of K.
7. Evaluated using accuracy and confusion matrix.
8. Visualized confusion matrix using Seaborn.

## ✅ Results
- *Accuracy:* Around 95–97% (may vary by run)
- *Confusion Matrix:* Shows correct predictions per class.

## 📷 Output Screenshot (if any)
Add screenshot of confusion matrix or output here (optional)

## ❓ Interview Questions with Answers

1. *How does the KNN algorithm work?*  
   It finds the K-nearest data points and uses majority vote for classification.

2. *How do you choose the right K?*  
   Test different values and choose the one with best accuracy on validation data.

3. *Why is normalization important in KNN?*  
   KNN uses distances, so features must be on the same scale.

4. *What is the time complexity of KNN?*  
   O(n) per prediction, where n = number of training samples.

5. *Pros and Cons of KNN?*  
   - ✅ Simple, no training time  
   - ❌ Slow prediction time, sensitive to noise

6. *Is KNN sensitive to noise?*  
   Yes, especially for small K values.

7. *How does KNN handle multi-class problems?*  
   It classifies based on majority vote among neighbors from all classes.

8. *What’s the role of distance metrics in KNN?*  
   Used to calculate similarity — Euclidean distance is common.
