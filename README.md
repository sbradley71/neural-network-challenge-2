# neural-network-challenge-2

# I used Xpert Learning Assistant when I became stuck on part of the challenge.

# Questions and Answers

# Is accuracy the best metric to use on this data? Why or why not?

## Accuracy may not be the best metric to use on this data, especially if the classes are imbalanced. In this case, the department accuracy is around 54.6%, which might not provide a complete picture of the model's performance. It's essential to consider other metrics like precision, recall, F1-score, or ROC-AUC, especially when dealing with imbalanced datasets.

# What activation functions did you choose for your output layers, and why?

## For both output layers I chose Softmax. This allows the outputs sum to 1 and represent probabilities for each class, facilitating better decision-making.

# Can you name a few ways that this model might be improved?

## Improve data preprocessing: Ensure data is properly cleaned, scaled, and encoded. Hyperparameter tuning: Experiment with different architectures, activation functions, learning rates, and regularization techniques to optimize model performance. Address class imbalance: Implement techniques like oversampling, undersampling, or using class weights to handle imbalanced classes. Increase training data: More data can help the model generalize better. Regularization: Add regularization techniques like dropout or L2 regularization to prevent overfitting. Experiment with different neural network architectures: Try different layer configurations, add more layers, or adjust the number of neurons in each layer to find the optimal architecture for the problem.