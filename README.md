# K-Nearest-Neighbor

**Iris and Digits Classification with K-Nearest Neighbors (KNN)**
This project demonstrates classification using the K-Nearest Neighbors (KNN) algorithm on two different datasets: the Iris dataset and the Digits dataset. It includes visualizing data distributions and evaluating the model's performance.

**Iris Dataset Classification**
This section involves classifying iris flowers into three species based on their sepal and petal measurements.

**Dataset**
The Iris dataset contains:
Four features: sepal length (cm), sepal width (cm), petal length (cm), petal width (cm).
Target: 0, 1, 2 representing the species: setosa, versicolor, and virginica.

**Steps**
**Data Loading and Exploration:**
Loaded the Iris dataset into a DataFrame.
Explored the dataset, including unique values and shape.

**Data Visualization:**
Visualized sepal length vs. sepal width for different species.
Visualized petal length vs. petal width for different species.

**Data Preparation:**
Created feature matrix X and target vector y.
Split the data into training and testing sets.

**Model Training and Evaluation:**
Trained a KNN classifier with k=10.
Evaluated the model on the test set using accuracy score.

**Digits Dataset Classification**
This section involves recognizing handwritten digits (0-9) using the Digits dataset from sklearn.

**Dataset**
The Digits dataset contains:
Pixel values of digit images.
Target: Digit labels (0-9).

**Steps**
**Data Loading and Exploration:**
Loaded the Digits dataset into a DataFrame.
Explored the dataset, including unique values and shape.

**Data Preparation:**
Created feature matrix X and target vector y.
Split the data into training and testing sets.

**Model Training and Evaluation:**
Trained a KNN classifier with k=5.
Evaluated the model on the test set using accuracy score.

**Results**
The models were evaluated using the accuracy score on both training and testing sets for the Iris and Digits datasets.

**Dependencies**
pandas
numpy
matplotlib
scikit-learn
