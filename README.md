### Online-learning-algorithm-implementation

This project demonstrates an online learning algorithm that updates its model incrementally as new data arrives, making it suitable for streaming or real‑time systems. The implementation uses SGDClassifier from scikit‑learn to build an online logistic regression model that learns in mini‑batches.

### 📌 Project Description

Online learning allows a model to update itself continuously instead of retraining from scratch.
In this project, an incremental logistic regression classifier is implemented using scikit‑learn’s SGDClassifier, which supports online updates through the partial_fit method.

A simulated binary classification dataset is generated and trained in small batches to mimic streaming data. After each batch update, the model’s accuracy is tracked, followed by a final evaluation on test data.

### 🧠 Key Features

Implements online/incremental learning using partial_fit

Simulates streamed training with mini‑batches

Tracks batch‑wise accuracy during training

Evaluates final model performance on test data
