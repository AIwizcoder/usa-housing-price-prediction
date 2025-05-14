USA Housing Price Prediction
This project is about predicting house prices in the USA using machine learning models. The dataset includes information like average income, house age, number of rooms, and area population. The goal is to train different regression models and compare their performance in estimating housing prices.

Dataset Details
The dataset includes the following columns:

Avg. Area Income – average income of residents in the area

Avg. Area House Age – average age of houses

Avg. Area Number of Rooms – average number of rooms

Avg. Area Number of Bedrooms – average number of bedrooms

Area Population – total population of the area

Price – target variable (house price)

Address – dropped, not useful for modeling

Models Used
Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Libraries and Tools
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Google Colab

How to Run

Clone this repo:
git clone https://github.com/AIwizcoder/usa-housing-price-prediction.git
cd usa-housing-price-prediction
Install dependencies:
pip install -r requirements.txt
Open the notebook:

Run the house_price_prediction.ipynb file on Google Colab or Jupyter Notebook. It covers data loading, preprocessing, training, and evaluation.

Project Workflow
Load and explore the data

Drop irrelevant columns (like Address)

Train multiple models

Evaluate using RMSE

Plot results and residuals

Results
Linear Regression is used as a basic benchmark

Tree-based models (Random Forest and Gradient Boosting) give better results

Random Forest performs the best overall in this case

License
This project is licensed under the MIT License. See the LICENSE file for more information.
