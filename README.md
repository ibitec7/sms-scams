# README

## Project Overview

This project utilizes machine learning techniques to classify and detect SMS scams, enhancing user awareness and protection against spam messages. By analyzing a dataset of 5,574 SMS messages, the project implements effective classification methods and tracks experiments for reproducibility.

## Key Highlights

- **Objective:** Develop a machine learning algorithm to identify and classify at least 90% of all SMS scams.
- **Dataset:** Utilized 5,574 SMS messages from Kaggle, labeled as spam or ham.
- **Algorithms:** Implemented Support Vector Classification (SVC), Logistic Regression, K-Nearest Neighbors (KNN), Naïve Bayes, and Random Forest.
- **Results:** The best model achieved 94% accuracy in classifying spam messages with minimal false positives.
- **Methodology:** Involved data cleaning, feature engineering, exploratory analysis, and model training.
- **Experiment Tracking:** Used MLFlow to log model performance metrics, hyperparameters, and classification reports. Trained model parameters are saved for reproducibility.
- **Impact:** Potential applications in law enforcement and mobile carrier systems to combat SMS scams.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/ibitec7/sms-scams.git
2. Navigate to the repository:
   ```bash
   cd sms-scams
3. Install the required packages:
   ```bash
   conda install -r requirements.txt

## Dataset
The dataset used in this project is the SMS Spam Collection Dataset, which consists of 5,574 SMS messages. Each message is labeled as either "spam" or "ham" (legitimate). The dataset is sourced from Kaggle.

## Results
The project successfully classifies SMS messages with an overall accuracy of 94%. The performance metrics for each model can be found in the MLFlow tracking UI.

## Acknowledgments
- The dataset is provided by Kaggle
- Special thanks to Professor Linyan Li for motivating the project
  
