# Heart Disease Prediction - Neural Network Classifier

A feedforward neural network for binary classification of heart disease risk, trained on structured healthcare data. Outperforms a logistic regression baseline by 11 percentage points.

## Results

| Model | Accuracy |
|---|---|
| Classify everything as 0(baseline) | 72.6% |
| Neural Network | **83.6%** |

## Dataset

TensorFlow's Heart Disease dataset (`heart.csv`) - 303 patients, 13 clinical features including age, cholesterol, resting blood pressure, and chest pain type.

## Approach

- Data cleaning, feature selection, and normalization
- Final model: Feedforward Neural Network (Keras/TensorFlow)
- Evaluation: Accuracy, Precision, Recall, Confusion Matrix

## Tech Stack

`Python` `TensorFlow/Keras` `Scikit-learn` `Pandas` `NumPy` `Google Colab`

## How to Run

1. Open the notebook in Google Colab
2. Run all cells - dataset loads automatically from the TensorFlow URL
3. No local setup needed

## Key Takeaway

Neural network achieves 83.6% accuracy vs 72.6% for a naive baseline model that classifies everything as 0, demonstrating the advantage of non-linear modelling on clinical tabular data.
