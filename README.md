Sales Prediction Using Python

A Machine Learning project that predicts product sales based on advertising expenditure across different marketing channels. The project uses Python for data analysis, visualization, model building, and prediction.

📌 Project Overview

Advertising plays an important role in influencing product sales. Understanding the relationship between advertising expenditure and sales can help businesses make better marketing decisions.

This project analyzes advertising data and applies Machine Learning regression techniques to predict sales based on advertising expenditure.

The project was developed as part of the Oasis Infobyte Data Science Internship (OIB-SIP).

🎯 Objectives

- Analyze the relationship between advertising expenditure and sales.
- Perform exploratory data analysis on the dataset.
- Visualize relationships between different advertising channels and sales.
- Prepare the data for Machine Learning.
- Train a regression model for sales prediction.
- Evaluate the performance of the trained model.
- Predict sales based on advertising expenditure.

📊 Dataset

The dataset contains advertising expenditure information along with corresponding sales values.

Important Features

Feature| Description
"TV"| Advertising expenditure through TV
"Radio"| Advertising expenditure through Radio
"Newspaper"| Advertising expenditure through Newspaper
"Sales"| Product sales — Target Variable

🔄 Project Workflow

Data Collection
       ↓
Data Loading
       ↓
Data Cleaning & Inspection
       ↓
Exploratory Data Analysis
       ↓
Data Visualization
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Sales Prediction

🔍 Exploratory Data Analysis

The project investigates how different advertising channels are related to product sales.

The analysis includes:

- Understanding the structure of the dataset.
- Checking for missing values.
- Analyzing statistical properties of the data.
- Studying the relationship between advertising expenditure and sales.
- Examining correlations between variables.
- Visualizing important relationships using graphs.

📈 Data Visualization

Visualizations are used to understand the impact of different advertising channels on sales.

The analysis includes visualizations such as:

- TV Advertising vs Sales
- Radio Advertising vs Sales
- Newspaper Advertising vs Sales
- Correlation analysis
- Distribution of sales
- Relationship between advertising expenditure and sales

These visualizations help identify which advertising channels have stronger relationships with sales.

🤖 Machine Learning

Since "Sales" is a continuous numerical variable, the project treats this as a regression problem.

The dataset is divided into:

- Training Set – Used to train the Machine Learning model.
- Testing Set – Used to evaluate the model on unseen data.

The advertising expenditure features are used as independent variables, while "Sales" is used as the target variable.

Features

TV
Radio
Newspaper

Target

Sales

📊 Model Evaluation

The trained model is evaluated using appropriate regression metrics to determine how accurately it predicts sales.

Common evaluation metrics include:

- R² Score – Measures how well the model explains variations in sales.
- Mean Absolute Error (MAE) – Measures the average absolute prediction error.
- Mean Squared Error (MSE) – Measures the average squared prediction error.
- Root Mean Squared Error (RMSE) – Measures prediction error in the same unit as the target.

💡 Key Insights

The analysis helps understand the relationship between advertising expenditure and product sales.

Some important observations include:

- Advertising expenditure has a measurable relationship with sales.
- Different advertising channels contribute differently to sales.
- TV advertising shows a strong relationship with sales in the dataset.
- Radio advertising also provides useful information for predicting sales.
- Newspaper advertising has a comparatively weaker relationship with sales.
- Regression-based Machine Learning can be used to estimate sales from advertising expenditure.

🛠️ Technologies & Libraries

Programming Language

- Python

Libraries

- Pandas – Data manipulation and analysis
- NumPy – Numerical computation
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine Learning and model evaluation

Development Environment

- Jupyter Notebook

📂 Project Structure

OIBSIP/
│
├── Sales Prediction Using Python.ipynb
│
└── README.md

▶️ How to Run the Project

1. Clone the Repository

git clone https://github.com/kanchanbiswas058/OIBSIP.git

2. Navigate to the Repository

cd OIBSIP

3. Install Required Libraries

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4. Launch Jupyter Notebook

jupyter notebook

Open:

Sales Prediction Using Python.ipynb

Run the notebook cells sequentially to reproduce the analysis, visualizations, model training, and predictions.

📓 Project Notebook

The complete implementation is available on GitHub:

Sales Prediction Using Python

https://github.com/kanchanbiswas058/OIBSIP/blob/main/Sales%20Prediction%20Using%20Python.ipynb

🚀 Future Improvements

- Compare multiple regression algorithms.
- Perform hyperparameter tuning.
- Use cross-validation for more reliable evaluation.
- Add more advertising and business-related features.
- Develop an interactive sales prediction application using Streamlit.
- Deploy the trained model as a web application.
- Build a dashboard for analyzing advertising performance.
- Explore advanced Machine Learning and ensemble techniques.

👨‍💻 Author

Kanchan Biswas

GitHub:
https://github.com/kanchanbiswas058

LinkedIn:
https://www.linkedin.com/in/kanchan-biswas-44988122a

⭐ Conclusion

This project demonstrates how Python and Machine Learning can be used to analyze advertising data and predict product sales.

Through data preprocessing, exploratory data analysis, visualization, regression modeling, and model evaluation, the project provides an end-to-end workflow for solving a real-world sales prediction problem.

The project also provides practical experience in Python, Pandas, NumPy, Data Visualization, Scikit-learn, Regression, and Machine Learning.
