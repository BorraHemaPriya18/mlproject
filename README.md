# Fashion MNIST Classification - ML Project

A machine learning project that classifies clothing items from the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset using multiple classifiers.

## Dataset

Fashion MNIST contains 70,000 grayscale images (28x28 pixels) across 10 clothing categories:

| Label | Class |
|-------|-------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

- Training set: 60,000 images
- Test set: 10,000 images

## Models Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVC)
- K-Nearest Neighbors (KNN)

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

## Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
```

## How to Run

1. Open `MLProject.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells sequentially.

## Project Structure

```
mlproject/
└── MLProject.ipynb   # Main notebook with all steps
```
