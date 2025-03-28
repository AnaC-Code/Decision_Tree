# Decision Tree Code Project

## Overview

This project contains two Jupyter Notebook files that implement decision tree models to analyze two different datasets. The models predict outcomes based on categorical and numerical features, converting categorical variables into numerical representations using the LabelEncoder method. The implementation is done using the Pandas and Scikit-Learn libraries.

This project is based on the tutorial videos available at:
[Decision Tree Tutorial](https://www.youtube.com/watch?v=PHxYNGo8NcI&list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw&index=10).

## Project Files

1. **salary.ipynb**
   * **Objective**: Predict whether a person's salary is more than $100K based on categorical features.
   * **Dataset**: `salaries.csv`
   * **Dataset Features**:
     * **Company** (Categorical)
     * **Job** (Categorical)
     * **Degree** (Categorical)
   * **Processing**:
     * Categorical features are converted to numerical values using `LabelEncoder`.
     * A decision tree classifier is trained on the transformed dataset.
2. **exercise.ipynb**
   * **Objective**: Predict whether a person survived based on key features.
   * **Dataset**: `titanic.csv`
   * **Dataset Features**:
     * **Pclass** (Categorical)
     * **Sex** (Categorical)
     * **Age** (Numerical)
     * **Fare** (Numerical)
   * **Processing**:
     * The categorical columns (**Pclass**, **Sex**) are converted to numerical values using `LabelEncoder`.
     * A decision tree classifier is trained on the transformed dataset.

## Requirements

The project relies on the following Python libraries:

* `pandas`
* `scikit-learn`

All dependencies are listed in `requirements.txt` and can be installed using:

```
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook files (`salary.ipynb` or `exercise.ipynb`).
2. Run the cells step by step to preprocess the data and train the decision tree models.
3. Analyze the results to understand how the decision tree makes predictions based on input features.

## License

This project is open-source and available for modification and distribution.
