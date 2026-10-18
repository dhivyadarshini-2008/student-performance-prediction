# Student Performance Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict whether a student passes or does not pass based on student-related information.

## Dataset
The project uses the Student Performance dataset from the UCI Machine Learning Repository.

- Dataset link: https://archive.ics.uci.edu/dataset/320/student+performance

## Machine Learning Models
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

## Data Preparation
- Loaded and explored the dataset
- Checked for missing values
- Created a Pass/Not Pass target using the final grade
- Split the data into 80% training and 20% testing sets
- Scaled numerical features and encoded categorical features

## Results

| Model | Accuracy |
|---|---:|
| Decision Tree | 88.61% |
| KNN | 77.22% |

- Confusion matrices were used to compare correct and incorrect predictions.

## Conclusion
The Decision Tree model performed better than KNN on the test dataset. This project helped demonstrate data preparation, model training, accuracy evaluation, and confusion matrix analysis.

## Requirements
- Python 3
- pandas
- matplotlib
- scikit-learn

## How to Run
- Open `student_performance_prediction.ipynb` in Google Colab or Jupyter Notebook and run the cells in order.
