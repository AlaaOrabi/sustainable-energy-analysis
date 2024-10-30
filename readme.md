This project performs exploratory data analysis (EDA) and machine learning (ML) on a global sustainable energy dataset. It provides insights into electricity access, energy consumption, and CO₂ emissions across countries and examines the relationship between these factors. Furthermore, the project uses machine learning models to predict CO₂ emissions based on energy indicators.

Table of Contents
Project Overview
Dataset
Project Structure
Requirements
Usage
Machine Learning Models
Results
Project Overview
The project includes:

Exploratory Data Analysis (EDA) - Visualizing trends in electricity access, energy consumption from various sources, and CO₂ emissions.
Machine Learning (ML) Pipeline - Building and evaluating models to predict CO₂ emissions using indicators related to energy consumption.
Dataset
The dataset used here is a CSV file (global-data-on-sustainable-energy.csv) containing information on electricity access, energy sources (fossil fuels, nuclear, renewables), and CO₂ emissions for different countries and years.

Project Structure
Data Loading and EDA: Loads the dataset, conducts descriptive statistics, and visualizes trends and distributions.
Feature Engineering and Preprocessing: Handles feature selection and scaling for ML models.
Machine Learning Pipeline: Trains multiple models and evaluates them on predicting CO₂ emissions.
Results Visualization: Plots results, including model performance comparisons and feature importance for the best model.
Requirements
Install dependencies using the following command:

bash
Copy code
pip install -r requirements.txt

Usage
Clone the repository:

bash
Copy code
git clone https://github.com/AlaaOrabi/sustainable-energy-analysis.git
Run the Jupyter Notebook or Python Script:


Review data summaries, visualizations, and initial findings about electricity access and CO₂ emissions.
Model Training and Evaluation:

After visualizing trends, train models to predict CO₂ emissions. The script will output model performance metrics, including RMSE and R² scores.
Machine Learning Models
The following models are included:

Linear Regression
Random Forest Regressor
XGBoost Regressor
Each model is evaluated using:

Root Mean Squared Error (RMSE): To measure prediction error.
R² Score: To indicate the model’s ability to explain variance in the data.
The best model’s feature importance is visualized to understand the significance of each energy indicator.

Results
EDA Results: Shows global trends in electricity access and CO₂ emissions over time, along with country-specific breakdowns of energy sources.
ML Model Performance: Compares models based on RMSE and R² Score. The actual vs. predicted CO₂ emissions plot for the best model visualizes model accuracy.
Feature Importance: For tree-based models, the importance of each energy indicator for CO₂ emissions prediction is displayed.
