# Handwritten Digit Recognition

This project implements a machine learning model to recognize handwritten digits using the MNIST dataset. The goal is to develop an accurate and efficient model capable of classifying images of handwritten digits (0-9).

## Project Overview

- **Dataset**: The project utilizes the MNIST dataset, which consists of 70,000 grayscale images of handwritten digits, each measuring 28x28 pixels.
- **Model Architecture**: A Multilayer Perceptron (MLP) neural network is used for classification. The model is designed to learn features and patterns from the input images through multiple hidden layers.
- **Libraries Used**: 
  - **Scikit-learn**: For model training, evaluation, and data preprocessing.
  - **NumPy**: For numerical computations.
  - **Matplotlib**: For visualizing results and performance metrics.
  
## Key Features

- **Data Preprocessing**: Images are normalized to improve model performance.
- **Model Training**: The MLP is trained using backpropagation and stochastic gradient descent.
- **Performance Evaluation**: The model's accuracy is assessed using confusion matrices and classification reports.

## Results

The trained model achieves an accuracy of over 95% on the test dataset, demonstrating its effectiveness in recognizing handwritten digits.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repositoryname.git
2. Navigate to the project directory:
   ```bash
   cd repositoryname
3. RUN the Jupyter Notebook:
   ```bash
   jupyter notebook Recognizing_HandWritten_Digits_in_Scikit_Learn.ipynb
