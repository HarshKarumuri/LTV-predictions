# LTV-predictions
Customer Lifetime Value Prediction
This project aims to predict Customer Lifetime Value (LTV) based on customer behavior using Python and machine learning. The primary objective is to identify high-value customers for targeted marketing strategies.

Project Overview
The project uses RFM (Recency, Frequency, and Average Order Value) analysis to create features from the customer transaction data. These features are then used to train a regression model to predict the Customer Lifetime Value (LTV) using the XGBoost Regressor.

Tools & Libraries
Python (for data analysis, feature engineering, and model building)

Pandas (for data manipulation)

Scikit-learn (for model training and evaluation)

XGBoost (for regression model)

Matplotlib & Seaborn (for visualizations)

FPDF (for generating the PDF report)

Dataset
The dataset used in this project is a marketing dataset containing customer information and transaction data. You can download the dataset from here.

Steps Involved
Data Preprocessing:

Load and clean the dataset.

Merge customer transactions with customer IDs.

Feature Engineering:

Calculate Recency, Frequency, and Average Order Value (AOV) for each customer.

Recency: Days since last purchase.

Frequency: Total number of purchases.

AOV: Average value of each purchase.

Model Building:

Split data into training and testing sets.

Train a XGBoost Regressor model to predict LTV.

Model Evaluation:

Evaluate the model performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Customer Segmentation:

Segment customers into Low, Medium, High, and VIP categories based on their predicted LTV.

Visualization:

Visualize the relationships between features and customer segments.

Plot customer segments using bar charts and scatter plots.

Report Generation:

Generate a professional PDF report with all findings, including visualizations.

Deliverables
Python Notebook: Contains all the code for data processing, feature engineering, model training, and evaluation.

Trained Model: The XGBoost model for predicting LTV.

Visualizations: Bar charts, scatter plots, and heatmaps that visualize the model's results.

PDF Report: A professionally designed report summarizing the project and insights.
