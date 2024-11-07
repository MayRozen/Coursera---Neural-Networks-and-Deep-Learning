# Logistic Regression Classifier for Cat Recognition

My first programming assignment in Coursera's course at Deep Learning! I have built a logistic regression classifier to recognize cats.
It is a part of my learning about Logistic Regression with a Neural Network mindset.

### Parameters:
- `X_train`: Training set (numpy array of shape `(num_px * num_px * 3, m_train)`)
- `Y_train`: Training labels (numpy array of shape `(1, m_train)`)
- `X_test`: Test set (numpy array of shape `(num_px * num_px * 3, m_test)`)
- `Y_test`: Test labels (numpy array of shape `(1, m_test)`)
- `num_iterations`: Number of iterations for optimization (default: `2000`)
- `learning_rate`: Learning rate for optimization (default: `0.5`)
- `print_cost`: Set to `True` to print the cost every 100 iterations (default: `False`)

### Output:
The function returns a dictionary `d` containing the following values:

- `costs`: A list of costs during optimization
- `Y_prediction_test`: Predictions on the test set
- `Y_prediction_train`: Predictions on the training set
- `w`: Learned weights
- `b`: Learned bias
- `learning_rate`: Learning rate used
- `num_iterations`: Number of iterations performed

