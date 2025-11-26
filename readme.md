# Sign Language Digits Deep Learning

![Sign Language Digits Dataset Cover](https://storage.googleapis.com/kaggle-datasets-images/3254697/5662543/c403c0802b40e3f5bb911c0fa9ea907c/dataset-cover.jpg?t=2023-05-13-11-04-09)

Two stage deep learning project based on the Sign Language Digits dataset (28x28 grayscale images of hand signed digits 0 to 9).  
Built as part of the Basic of Deep Learning course at Colman (2024).

This repository shows the progression from a fully manual NumPy neural network to a production style Keras multiclass model.

---

## Milestone 1 — NumPy Neural Network (From Scratch)
Binary classification: digit 4 vs digit 9

Focus:
- Fully manual forward propagation
- Fully manual backpropagation
- Binary Cross Entropy loss
- Gradient Descent optimization
- Hyperparameter experiments

Model Summary:
- Input: 784 features (28x28)
- Hidden layer: 10 neurons (sigmoid)
- Output: 1 neuron (sigmoid)
- Test accuracy: up to 100 percent

Folder:
milestone1_numpy_from_scratch/

[Open in Google Colab](https://colab.research.google.com/drive/13N-uFiFJmC86ny3Jm6PLu_4rLRci4OZv?usp=sharing)

Report:  
In depth experimental report is provided as a PDF inside the folder.

---

## Milestone 2 — Keras Neural Network (Multiclass)
Multiclass classification: all 10 digits

Focus:
- Keras Sequential model
- ReLU hidden layers
- Softmax output
- Adam optimizer
- Categorical Cross Entropy
- Architecture and hyperparameter tuning

Best Model Summary:
- Input: 784 neurons
- Hidden layers: 128 to 32 (ReLU)
- Output: 10 neurons (Softmax)
- Batch size: 16
- Epochs: 20
- Test accuracy: up to 99.1 percent

Folder:
milestone2_keras_multiclass/

[Open in Google Colab](https://colab.research.google.com/drive/1i44NtSxB7JKdu9WKNZ4xFFPoT1DC9yzY?usp=sharing)

Report:  
In depth experimental report is provided as a PDF inside the folder.

---

## Running the Project
All notebooks are designed to run on Google Colab and contain Colab specific setup code.  
For easiest use, open them using the links above.

---

## Authors
- Amos Zohar  
- Gal Havshush