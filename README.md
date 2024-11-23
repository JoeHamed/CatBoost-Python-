# CatBoost Classifier Example

This repository demonstrates the use of the CatBoost library for training a classification model. The example includes importing a dataset, preprocessing, splitting the data, training the model, and evaluating its performance.

## Getting Started

### Prerequisites
Ensure you have Python installed and the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `catboost`

Install the required packages using:
```bash
pip install numpy pandas matplotlib scikit-learn catboost
```
### Dataset

- The example uses a Data.csv file, where:
  - The features (`X`) are all columns except the last one.
  - The target variable (`y`) is the last column.
- Ensure your dataset follows this structure.

## Code Explanation
### Importing the Dataset
- The dataset is read into a pandas DataFrame and split into features (`X`) and target (`y`).

### Splitting the Dataset
- The dataset is split into training and testing sets using an 80-20 split.

### Training CatBoost Classifier
- The CatBoostClassifier is used to train the model on the training data. Default parameters are used for simplicity.

### Accuracy
- The model achieves an accuracy of `97.26%`, with a standard deviation of `2.03%` (example values, may vary depending on your dataset).
  
