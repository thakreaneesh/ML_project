Rainfall Prediction Project
Overview
This project focuses on predicting rainfall using machine learning algorithms based on daily weather observations from various Australian weather stations. The goal is to develop a reliable model to forecast whether it will rain the following day, enabling better decision-making for individuals and businesses affected by weather conditions.

Contents
data/: This directory contains the dataset used for training and testing the models.
notebooks/: Jupyter notebooks containing the code for data preprocessing, exploratory data analysis, model training, and evaluation.
reports/: Final report detailing the project, methodologies, results, and conclusions.
requirements.txt: List of dependencies required to run the project.
Algorithms Used
The following machine learning algorithms were implemented in this project:

Logistic Regression: A statistical method for binary classification that predicts the probability of an event occurring.
Decision Tree: A model that makes decisions based on the features of the data, creating a tree-like structure to determine outcomes.
Neural Network: A model inspired by the structure of the human brain, capable of capturing complex patterns in data.
Random Forest: An ensemble method that combines multiple decision trees to improve accuracy and control overfitting.
Dataset
The dataset consists of approximately 10 years of daily weather observations, with the target variable indicating whether it rained the next day (Yes or No). Note that the variable Risk-MM was excluded from training to prevent data leakage.

Installation
To run this project, make sure to have Python installed along with the required libraries. You can install the dependencies using:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/rainfall-prediction.git
cd rainfall-prediction
Open the Jupyter notebooks in the notebooks/ directory to explore the data analysis and model training process.
Refer to the reports/ directory for a comprehensive overview of the project findings and conclusions.
Contributions
This project was solely developed by Aneesh Thake.

License
This project is licensed under the MIT License.

Acknowledgements
The dataset is sourced from Kaggle.
Special thanks to the contributors of the libraries used in this project.
