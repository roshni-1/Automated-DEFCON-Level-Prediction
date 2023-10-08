# Project Name: Automated DEFCON Level Prediction

## Overview
This project focuses on automating the prediction of DEFCON (Defense Readiness Condition) levels, a vital aspect of national defense and military preparedness. By leveraging machine learning techniques and exploratory data analysis (EDA), this project aims to provide accurate and timely assessments of national security readiness based on various military and diplomatic factors.

## Project Objectives
1. **Automate DEFCON Prediction:** Develop a machine learning model to automate the prediction of DEFCON levels based on synthesized military data.
2. **Enhance National Security:** Enable timely and accurate assessment of national security readiness, aiding defense forces in strategic decision-making.
3. **Improve Efficiency:** Replace manual DEFCON assessment methods with an efficient and precise automated system, reducing response time during critical situations.

## Key Features
- **Data Processing:** Thorough preprocessing of the dataset, including handling missing values, feature scaling, and engineering new features for meaningful insights.
- **Exploratory Data Analysis (EDA):** In-depth analysis using various visualizations and statistical techniques to uncover patterns, outliers, and correlations within the data.
- **Machine Learning Model:** Implementation of a Random Forest Classifier for DEFCON level prediction, with hyperparameter tuning for optimal performance.
- **Model Evaluation:** Utilization of accuracy as the primary evaluation metric to assess the model's reliability.

## Folder Structure
project-root/
│
├── data/
│ ├── train_data.csv # Training dataset containing synthesized military data
│ ├── test_data.csv # Test dataset without DEFCON_Level column for predictions
│
├── notebooks/
│ ├── EDA_and_Modeling.ipynb # Jupyter Notebook containing data analysis and machine learning modeling
├── requirements.txt # Python dependencies required for the project
├── README.md # Project README file (you are here)

## Getting Started
1. **Clone the Repository:**

git clone <[repository-url](https://github.com/roshni-1/Automated-DEFCON-Level-Prediction)https://github.com/roshni-1/Automated-DEFCON-Level-Prediction>
cd project-root/

2. **Install Dependencies:**
pip install -r requirements.txt


3. **Run Jupyter Notebook:**
jupyter notebook notebooks/DEFCON-Level predection.ipynb


4. **Explore the Code:**
- Understand the data preprocessing steps in `src/data_preprocessing.py`.
- Explore the machine learning model in `src/model.py`.
- Analyze the dataset and model implementation in the Jupyter Notebook.

## How to Contribute
1. Fork the project.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to the forked repository.
5. Create a pull request for your changes.





