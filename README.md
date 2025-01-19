# Credit Score Classifier

## Overview
This project involves building a machine learning model to classify credit scores using customer data. The pipeline integrates data preprocessing, feature engineering, and advanced modeling techniques to assess creditworthiness effectively.

## Features
- **Data Preprocessing:** Handled duplicates, missing values, and performed feature engineering using pandas and NumPy.
- **Modeling:** Developed a neural network model with TensorFlow and Keras and implemented a decision tree model for comparison.
- **Regularization and Dropout:** Applied these techniques to improve model generalization and prevent overfitting.
- **Visualization:** Utilized Matplotlib for exploratory data analysis and to evaluate model performance.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - TensorFlow and Keras for machine learning
  - pandas and NumPy for data manipulation
  - scikit-learn for decision tree implementation
  - Matplotlib for data visualization

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd credit_score_classifier
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place your training and testing datasets in the `data/` directory.
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook credit_score_classifier.ipynb
   ```
3. Follow the steps in the notebook to preprocess data, train the model, and evaluate performance.

## Project Structure
```
credit_score_classifier/
├── data/
│   ├── train.csv
│   ├── test.csv
├── credit_score_classifier.ipynb
├── README.md
└── requirements.txt
```

## Results
The project demonstrated effective classification of credit scores, showcasing the strengths of both neural network and decision tree models. Regularization and dropout significantly enhanced model accuracy by reducing overfitting.

## Acknowledgments
This project is inspired by the need for better financial decision-making tools and sustainable credit assessment practices.