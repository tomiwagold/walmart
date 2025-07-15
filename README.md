# Walmart Weekly Sales Prediction

## Project Overview
This project focuses on predicting Walmart's weekly sales using machine learning. Using historical data, the goal was to build an accurate model to forecast sales patterns and assist in planning and decision making. The project also includes an interactive Streamlit web app deployed locally via PyCharm for real-time predictions.

## Objectives
- Predict Walmart weekly sales using historical data.
- Clean and preprocess the data for better model performance.
- Implement and evaluate machine learning models.
- Deploy the model using Streamlit for interactive user input and output.

## Dataset
The dataset was obtained from Kaggle and includes:
- Store: Unique ID for each store
- Date: Week of the sales record
- Weekly_Sales: Target variable - total sales for the stores
- Holiday: Indicates if the week includes a major holiday
- Temperature, Fuel_Price, CPI, Unemployment: External factors potentially affecting sales

## Methodology
1. **Data Cleaning & Preprocessing:**
   - Checked for and handled missing values
   - Converted Date to datetime format and extracted new features: Year and Month
   - Dropped the original Date column after feature extraction
   - Removed outliers

2. **Exploratory Data Analysis (EDA):**
   - Plotted sales trends and seasonal effects
   - Analyzed the effect of holidays on sales

3. **Modeling:**
   - Applied **Random Forest Regressor** for prediction
   - Evaluated the model using R² Score and RMSE
   - Achieved an accuracy of **0.95** on the test set

4. **Deployment:**
   - Built an interactive **Streamlit** web app
   - Allowed users to input data and get instant predictions
   - Deployed and tested via **PyCharm**

## Tools & Technologies
- **Languages & IDE:** Python, PyCharm
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit

## Results
- The **Random Forest** model achieved an R² score of **0.95**.
- The Streamlit app works efficiently for generating predictions based on user inputs.

## Conclusion
This project showcases the application of machine learning in retail sales forecasting. The model helps predict weekly sales based on historical data and allows for real-time predictions through a user-friendly interface built with Streamlit.




*Interact with the Streamlit Web App Here:* [Walmart Weekly Sales Prediction](https://walmart-weekly-sales-prediction-taku3g9yny7iymikoi6cfv.streamlit.app/)
