# DiseasePrediction

This project is a disease prediction system using machine learning models to predict diseases based on symptoms. The system utilizes three different classifiers: Support Vector Machine (SVM), Gaussian Naive Bayes, and Random Forest, combined using an ensemble method to improve prediction accuracy.

## Table of Contents:

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Prediction Function](#prediction-function)
- [Results](#results)

## Installation
To get started with this project, clone the repository and install the necessary packages:
1. Clone the repository:
   ```sh
   git clone https://github.com/kushalmehta2004/DiseasePrediction
2. Navigate to the project directory.

Make sure you have the following libraries installed:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- scipy

## Usage
1. Load the dataset: Import the training.csv file to train the model
2. Train the Models: Execute the Jupyter Notebook to train the machine learning models using the training dataset.
3. Make Predictions: Use the predictDisease function to predict diseases based on symptoms.

## Data
The dataset used for this project includes a list of symptoms and the corresponding disease labels. Ensure that the datasets are properly formatted and preprocessed before use.

1. Training Data
Features: Symptoms encoded as binary values.
Labels: Disease names or codes.
2. Test Data:
A separate dataset used to evaluate model performance.

## Models
The project utilizes the following machine learning models:

1. Support Vector Machine (SVM): A powerful classifier known for its accuracy in high-dimensional spaces.
2. Gaussian Naive Bayes: A simple yet effective probabilistic classifier.
3. Random Forest: An ensemble method that combines multiple decision trees to improve accuracy and prevent overfitting.

## Prediction Function
The "predictDisease" function allows users to input symptoms and receive predicted diseases as output. The symptoms should be provided as a comma-separated string.

## Results
![image](https://github.com/user-attachments/assets/e5ce75cf-c6b5-474a-a0ee-98a7ef71290e)
![image](https://github.com/user-attachments/assets/372c1ae4-04df-49ac-9622-75115b01491e)


