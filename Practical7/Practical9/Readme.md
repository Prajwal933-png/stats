🌸 KNN Classification on Iris Dataset

This project demonstrates how to implement a K-Nearest Neighbors (KNN) classifier on the classic Iris dataset using Python and Scikit-Learn.
The workflow includes EDA, preprocessing, model training, evaluation, error analysis, and decision boundary visualization.

📘 Project Overview

The Iris dataset contains 150 samples belonging to three flower species:

Setosa

Versicolor

Virginica

Each sample includes 4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

The goal is to classify the species using the KNN algorithm.

🚀 Steps Performed
1️⃣ Exploratory Data Analysis (EDA)

Performed using:

head()

describe()

groupby()

Helps in understanding data distribution and class-wise differences.

2️⃣ Feature Scaling

Since KNN is a distance-based algorithm, feature scaling is essential.
Used StandardScaler to normalize values.

3️⃣ Model Training
Split dataset into training (80%) and testing (20%) and trained the model


4️⃣ Accuracy & Confusion Matrix

Evaluated predictions using:

confusion_matrix()

accuracy_score()

This helps understand model’s correctness and misclassifications.

5️⃣ Classification Report

Generated report containing:

Precision

Recall

F1-score
for all three classes.

6️⃣ Error Rate Comparison

Computed error rate for K = 1 to 40 to analyze how K impacts model performance.

7️⃣ Error Plot

Plotted Error Rate vs K Value to visually identify the optimal K.

8️⃣ Best K Value

Automatically selected the K value that results in minimum error rate.

9️⃣ Decision Boundary Visualization

Created a 2D visualization using the first two scaled features:

Shows class regions

Highlights test points

Uses best K value

This helps interpret how KNN separates different classes.


📈 Results

KNN performs extremely well on the Iris dataset due to its simple and well-separated classes.

The best K typically ranges between 3 and 7, based on the error curve.

Decision boundary plot clearly shows distinct regions for each species.

🏁 Conclusion

This project covers the complete practical workflow of applying KNN to a real dataset, including EDA, preprocessing, model building, evaluation, error analysis, and visualization. It serves as a solid introduction to supervised machine learning using Python.
Split dataset into training (80%) and testing (20%) and trained the model3️⃣ Model Training

