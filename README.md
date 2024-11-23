# Objective
The goal of this project is to predict the number of vehicles and signals in an image using ensemble methods. Multiple base models, including pre-trained and custom architectures, were trained and combined to achieve high accuracy in predictions.

# Key Highlights
Base Models:

ResNet50: Pre-trained convolutional neural network (CNN) with selective fine-tuning.
ResNet101: A deeper variant of ResNet with flexible training configurations.
ConvNeXt: Modern convolutional architecture leveraging fine-tuning techniques.
Vanilla CNN: A custom-built CNN for baseline performance comparison.
Mean Model: Simple baseline predicting the average value of vehicle and signal counts.
Ensemble Techniques:

Simple Average: Combined predictions using arithmetic mean.
Linear Regression: Weighted ensemble using regression on the base model outputs.
XGBoost: Advanced gradient boosting to learn from the outputs of the base models.
Fine-Tuning:

Fine-tuned pre-trained backbones by unfreezing the last 5 layers.
Applied L2 regularization and dropout for regularization to prevent overfitting.
Metrics:

Loss: Mean Squared Error (MSE).
Metric: Mean Squared Error (MSE).
# Tools and Frameworks
Python: Programming language for implementation.
TensorFlow/Keras: Framework for building and training models.
NumPy: Numerical computations for preprocessing and ensemble techniques.
XGBoost: Gradient boosting framework for ensemble learning.
