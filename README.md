# Tutorial Modelling Data Titanic

Tutorial ini akan akan mengolah data Titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisite

1. Download data [here!](https://www.kaggle.com/code/alexisbcook/titanic-tutorial)
2. Instalasi dengan `pip install requirements.txt`

## Getting Started

- Datset Splitting
- Training
- Model Validation

### Dataset Splitting

Split data into training, validation and test sets
```code
x_train, y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape
```

## Reference

1. Di scikit-learn documentation