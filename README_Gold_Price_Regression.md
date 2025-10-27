# Gold Price Prediction using Regression Model

## 📘 Overview
This project focuses on predicting gold prices using a **Regression Model**.  
By analyzing historical financial indicators, the model learns patterns that help forecast future gold prices.  
The project includes a correlation heatmap, data preprocessing, model training, evaluation, and comparison between actual and predicted values.

## 📊 Dataset
The dataset used for this project is the **GLD Price Dataset** from Kaggle.  
It includes historical data of gold prices along with related market indicators.

**Dataset Source:** [Kaggle - Gold Price Data](https://www.kaggle.com/datasets)

### Columns:
- **Date** – The date of the record  
- **SPX** – S&P 500 index value  
- **GLD** – Gold ETF closing price (Target variable)  
- **USO** – United States Oil Fund price  
- **SLV** – Silver ETF price  
- **EUR/USD** – Currency exchange rate  

## 🧠 Methodology
1. **Data Exploration**
   - Load the dataset using Pandas
   - Check for null values and data types
   - Visualize feature relationships using a **correlation heatmap**
2. **Feature Selection**
   - Identify independent features and target variable (GLD)
3. **Train-Test Split**
   - Split data into 80% training and 20% testing using `train_test_split()`
4. **Model Training**
   - Apply a **Regression Model** (e.g., Linear Regression, RandomForestRegressor)
   - Fit the model on training data
5. **Model Evaluation**
   - Predict values on the test data
   - Compare **Actual vs Predicted** prices
   - Calculate performance metrics such as:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score

## 📈 Results
- The regression model efficiently predicts gold prices with low error.  
- Visual comparison between **Actual** and **Predicted** prices confirms strong model accuracy.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gold-price-regression.git
   cd gold-price-regression
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook k18.ipynb
   ```

## 📊 Visualization
- Correlation Heatmap  
- Actual vs Predicted Scatter Plot  
- Error Metrics Display

## 💡 Future Improvements
- Integrate **LSTM** for time-series prediction  
- Add real-time gold price API for live forecasting  
- Deploy the model using Flask or Streamlit web app  

## 👩‍💻 Author
**Elavarasi Chinnadurai**  
Regression Analysis | Data Science | Predictive Modeling  

---
© 2025 Elavarasi Chinnadurai. All rights reserved.
