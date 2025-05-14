This repository contains two files focused on machine learning and AI, covering topics such as classification, dimensionality reduction, neural networks, and regularization techniques. These files demonstrate practical implementations of:

- Multinomial Logistic Regression with PCA

- Neural Networks (DNN and CNN)

- Model evaluation and comparison

Techniques used:

Dimensionality Reduction: PCA for feature selection.

Regularization: L2 penalty and dropout to prevent overfitting.

Activation Functions: ReLU (hidden layers) and Softmax (output).

Evaluation Metrics: Accuracy, precision, recall, F1-score, and confusion matrices.

Key Files
1. Logistic Regression and Neural Network Comparison.qmd

  Task: Classify bat families using acoustic features.

  Results: Neural Network (20 hidden neurons) achieved 91.4% accuracy on test data.

  PCA + Logistic Regression: 87.5% accuracy.

2. Neural Network and CNN Model Comparison with Regularization.qmd

  Task: Recognize 19 human activities from motion sensor data.

  Results: CNN model achieved 98% accuracy, outperforming DNNs.

  Challenging activities: moving_elevator (F1: 0.91).

  Easiest activities: walking, sitting (F1: 1.0).

Technical Stack
- Languages: R (for PCA/Logistic Regression), Python (Keras/TensorFlow for neural networks).

- Libraries: nnet, keras, tensorflow, caret.

- Methods: Cross-validation, hyperparameter tuning, one-hot encoding.
