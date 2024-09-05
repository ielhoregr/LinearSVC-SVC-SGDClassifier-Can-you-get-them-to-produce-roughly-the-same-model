# LinearSVC-SVC-SGDClassifier-Can-you-get-them-to-produce-roughly-the-same-model
# Linear SVM Comparison on Iris Dataset

## Objective
The goal of this project is to compare the performance of three linear classifiers—`LinearSVC`, `SVC`, and `SGDClassifier`—on a linearly separable subset of the Iris dataset. The focus is to see if we can get them to produce roughly the same model using the appropriate kernel and regularization parameters.

## Dataset
- **Iris Dataset**: We use the Iris dataset, focusing on two features: `petal length` and `petal width`, and two classes: `Setosa` and `Versicolor`.
- The dataset is **linearly separable**, making it suitable for linear SVM models.

## Steps
1. **Data Preprocessing**: We scale the features using `StandardScaler` to ensure proper training of the models.
2. **Models**:
    - `LinearSVC`: Hinge loss with a linear kernel.
    - `SVC`: Support Vector Classifier with a linear kernel.
    - `SGDClassifier`: Stochastic Gradient Descent with hinge loss.
3. **Visualization**: The decision boundaries of the three classifiers are plotted to compare their performance.

## Results
All three classifiers produced comparable models with similar decision boundaries when trained on the same dataset.

## Conclusion
By selecting the appropriate kernel and regularization parameter, we can achieve models with comparable performance for linear classification.

