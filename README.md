# Decision Tree Classifier

This repository contains an implementation of a Decision Tree Classifier in Python. Decision Trees are a powerful and interpretable machine learning algorithm used for both classification and regression tasks. This project focuses on building a Decision Tree Classifier for classification tasks.

## Features

- **Simple Implementation**: The Decision Tree Classifier is implemented in Python using standard libraries like NumPy and scikit-learn, making it easy to understand and modify.
  
- **Customizable**: Users can customize the hyperparameters of the Decision Tree, such as maximum depth, minimum samples split, and criterion (Gini impurity or entropy), to suit their specific needs.
  
- **Evaluation Metrics**: The classifier provides functions to evaluate the performance of the trained model using common metrics such as accuracy, precision, recall, and F1-score.
  
- **Visualization**: The Decision Tree can be visualized using graphviz to understand its structure and decision-making process.


2. Import the `DecisionTreeClassifier` class and use it in your Python code:

    ```python
    from decision_tree import DecisionTreeClassifier

    # Create an instance of the Decision Tree Classifier
    clf = DecisionTreeClassifier(max_depth=3)

    # Train the classifier
    clf.fit(X_train, y_train)

    # Make predictions
    predictions = clf.predict(X_test)

    # Evaluate the model
    accuracy = clf.evaluate(X_test, y_test)
    ```

## Example

Check out the `decision_trees.ipynb` Jupyter Notebook for a detailed example of how to use the Decision Tree Classifier on a sample dataset.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

