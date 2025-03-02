# 🏡 House Price Prediction using XGBoost

## 🔍 About This Project
This project builds a machine learning model to predict house prices based on the California housing dataset. The model utilizes the XGBoost Regressor for high accuracy. The project includes data preprocessing, feature analysis, model training, and evaluation.

---

## 🛠 Tech Stack
- **📌 Languages:** Python
- **📊 Machine Learning:** XGBoost, Scikit-learn
- **📈 Data Processing & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **🔧 Model Evaluation:** Mean Absolute Error (MAE), R-squared Score

---

## 📂 Project Structure
📂 House_Price_Prediction/

│── 📜 House_price_prediction.ipynb   # Jupyter Notebook with code  

│── 📂 data/                           # Contains dataset (if stored separately)  

│── 📂 models/                         # Saved trained model (if needed)  

│── 📜 requirements.txt                # Dependencies  

---

## 💡 Features
✔️ Loads the California Housing Dataset using fetch_california_housing

✔️ Performs Exploratory Data Analysis (EDA) with correlation heatmaps 📊

✔️ Splits the data into training and testing sets

✔️ Trains an XGBoost Regressor Model for accurate price prediction 🚀

✔️ Evaluates model performance using MAE & R² Score 📉

---

## 🚀 How to Run This Project
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   
2. **Install the dependancies and run Flask app**  
   ```bash
   pip install -r requirements.txt

3. **Run the Jupyter notebook**
   ```bash
   jupyter notebook House_price_prediction.ipynb

---

## 📊 Model Performance
- Mean Absolute Error (MAE): 0.22387540906811954 (for test data)
- R² Score: 0.8338000331788725 (for test data)

---

## 🤖 Future Enhancements
🚀 Deploy as a Flask API for real-world use

📊 Add feature engineering for better accuracy

💡 Implement Hyperparameter Tuning to optimize the model
