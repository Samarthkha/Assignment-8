# Assignment - 8 : Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## Objective

The objective of this project is to build an Artificial Neural Network (ANN) that can recognize handwritten digits from 0 to 9 using the MNIST dataset. The project demonstrates the complete deep learning workflow, including data preprocessing, model training, evaluation, and performance visualization.

---

## Dataset

- **Dataset Name:** MNIST Handwritten Digits Dataset
- **Dataset Link:** https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Methodology

The project was completed in the following steps:

1. Loaded the MNIST dataset using Pandas.
2. Explored the dataset by checking its shape, information, and sample records.
3. Displayed a sample handwritten digit.
4. Checked for missing values.
5. Separated input features and target labels.
6. Normalized the pixel values to improve model performance.
7. Split the dataset into training and testing sets.
8. Converted the target labels into one-hot encoded vectors.
9. Built an ANN model with two hidden layers.
10. Trained the model for 10 epochs.
11. Evaluated the model using test accuracy, confusion matrix, and classification report.
12. Plotted accuracy and loss graphs to analyze the training process.

---

## Model Architecture

The Artificial Neural Network consists of:

- **Input Layer:** 784 input neurons (28 × 28 pixels)
- **Hidden Layer 1:** 128 neurons with ReLU activation
- **Hidden Layer 2:** 64 neurons with ReLU activation
- **Output Layer:** 10 neurons with Softmax activation

**Optimizer:** Adam

**Loss Function:** Categorical Crossentropy

**Evaluation Metric:** Accuracy

---

## Results

The model successfully learned to recognize handwritten digits and achieved a high accuracy on the test dataset (around 96%). The training and validation accuracy improved with each epoch, while the loss decreased steadily. The confusion matrix and classification report showed that the model correctly classified most handwritten digits.

---

## Conclusion

This project helped me understand how Artificial Neural Networks are used for image classification. By preprocessing the data, training the ANN, and evaluating its performance, I gained practical experience with deep learning using TensorFlow and Keras. Overall, the model performed well and demonstrated that ANN can effectively recognize handwritten digits from the MNIST dataset.

---

## Project Files

```
Assignment-8.ipynb
README.md
