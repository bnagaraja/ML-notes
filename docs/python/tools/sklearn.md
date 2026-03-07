# What is scikit-learn?
Scikit-learn (also called sklearn) is a popular open-source Machine Learning library for Python.
It provides simple and efficient tools for:

- Classification
- Regression
- Clustering
- Model evaluation
- Data preprocessing

It is built on top of:

- NumPy
- SciPy
- Matplotlib

## Why scikit-learn is Important?

scikit-learn is the best starting point because:

✔ Easy to use
✔ Clean and consistent API
✔ Great documentation
✔ Used in real industry projects

## What Can You Do With It?

1️⃣ Classification

  - Logistic Regression
  - KNN
  - Decision Trees
  - Random Forest
  - SVM

??? example "Example:"
    ```python
    from sklearn.linear_model import LogisticRegression
    ```

2️⃣ Regression

  - Linear Regression
  - Ridge / Lasso
  - Random Forest Regressor

??? example "Example:"
    ```python
    from sklearn.linear_model import LinearRegression
    ```

3️⃣ Clustering

  - K-Means
  - DBSCAN
  - Hierarchical clustering

4️⃣ Data Preprocessing

  - Scaling (StandardScaler)
  - Encoding categorical data
  - Handling missing values

5️⃣ Model Evaluation

  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix
  - Cross-validation

??? example "⚙️ Simple Example"
    ```python
        from sklearn.linear_model import LinearRegression
        import numpy as np

        X = np.array([[1], [2], [3]])
        y = np.array([2, 4, 6])

        model = LinearRegression()
        model.fit(X, y)

        print(model.predict([[4]]))  # Output: 8
    ```
The model learned:  **y = 2x**