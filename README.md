# Flight-Ticket-Price-Prediction
 
 ## Project Overview

This project predicts airline ticket prices using Machine Learning Regression techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment through an interactive Streamlit application.

The goal is to help users estimate flight ticket prices based on travel details such as airline, source, destination, duration, and number of stops.

## Objectives
Perform data cleaning and preprocessing
Handle missing values and categorical features
Conduct Exploratory Data Analysis (EDA)
Train multiple regression models
Compare model performance
Predict flight ticket prices accurately
Deploy the model using Streamlit
## Dataset Features

The dataset contains flight-related information including:

Airline
Source
Destination
Total Stops
Journey Day
Journey Month
Departure Time
Arrival Time
Duration
Ticket Price (Target Variable)
## Exploratory Data Analysis

The project includes visualizations to understand:

Ticket Price Distribution
Airline-wise Price Comparison
Source vs Destination Analysis
Impact of Number of Stops on Price
Seasonal Price Trends
Correlation Analysis
Key Insights
Flight prices vary significantly across airlines.
More stops generally increase ticket prices.
Seasonal demand impacts airfare.
Flight duration has a strong influence on ticket cost.
## Machine Learning Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
K-Nearest Neighbors (KNN) Regressor
## Model Evaluation Metrics

The models are evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

The model with the highest R² score is selected as the final prediction model.

## Streamlit Application Features
Interactive flight detail input
Real-time ticket price prediction
User-friendly dashboard
Automated feature encoding
Machine Learning powered fare estimation
User Inputs
Airline
Source City
Destination City
Number of Stops
Journey Date
Departure Time
Flight Duration
Output
Estimated Flight Ticket Price (₹)
## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn
Streamlit
## Project Structure
├── flight_ticket.xls
├── Flight Ticket Price Prediction.ipynb
├── app.py
├── README.md
## How to Run
1. Clone Repository
git clone <repository-url>
cd flight-ticket-price-prediction
2. Install Dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn streamlit
3. Run Streamlit App
streamlit run app.py
## Future Improvements
Hyperparameter tuning
Advanced ensemble models
Real-world flight API integration
Model deployment on cloud platforms
Price trend forecasting
## Author

Shameel M

Machine Learning | Data Analytics | Python Developer

⭐ Conclusion

This project demonstrates a complete machine learning pipeline for flight ticket price prediction, from data preprocessing and EDA to model building and deployment. It provides an intuitive way for users to estimate airfare and understand factors affecting ticket prices.
