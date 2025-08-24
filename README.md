# Bank-Term-Deposit-Prediction

## 📌 Project Overview
This project analyzes marketing campaign data from a Portuguese bank to predict whether a client will subscribe to a **term deposit**.  
Using machine learning techniques, we clean, preprocess, and build predictive models to improve customer targeting and campaign efficiency.

---

## 📊 Dataset
- **File:** `bankmarketing.csv`  
- **Source:** Direct marketing campaigns of a Portuguese banking institution  
- **Target Variable:** `y` (whether the client subscribed to a term deposit: `yes` → `1`, `no` → `0`)  

### Key Features
- **Demographics:** age, job, marital status, education  
- **Financial:** balance, loan, housing loan  
- **Campaign-related:** contact type, campaign duration, number of contacts  
- **Socio-economic indicators:** employment variation rate, consumer price index, euribor rate  

---

## 🎯 Objectives
- Explore and understand customer behavior  
- Preprocess and encode categorical/numerical features  
- Train classification models for subscription prediction  
- Evaluate models using accuracy, precision, recall, and F1-score  

---

## ⚙️ Technologies Used
- **Python**  
- **Pandas, NumPy** → data analysis  
- **Scikit-learn** → ML models, preprocessing, evaluation  
- **Matplotlib, Seaborn** → data visualization  

---

## 🧑‍💻 Project Workflow
1. **Data Loading & Cleaning**
   - Import dataset  
   - Handle missing values  
   - Encode target variable (`yes/no` → `1/0`)  

2. **Exploratory Data Analysis (EDA)**
   - Visualize categorical & numerical features  
   - Identify important correlations  

3. **Data Preprocessing**
   - One-Hot Encoding for categorical variables  
   - Standardization for numerical features  
   - Train-test split  

4. **Model Building**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  

5. **Model Evaluation**
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1-score  

---

## 📈 Results
- Built baseline logistic regression and tree-based models  
- Random Forest provided the best performance with higher recall & F1-score  
- Identified important predictors such as **duration of contact, balance, and job type**  

---

## 🚀 How to Run

Clone this repository:
```bash
git clone https://github.com/your-username/bank-term-deposit-prediction.git

Navigate to the folder:
cd bank-term-deposit-prediction

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook Bank_Term_Deposit_Summary.ipynb

📌 Future Work

Hyperparameter tuning for better model performance

Testing advanced ML models (XGBoost, LightGBM)

Deploying the best model as a web app

📜 License

This project is licensed under the MIT License.


------

