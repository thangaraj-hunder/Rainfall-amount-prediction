# 🌧️ Rainfall Prediction using Machine Learning

## 📘 Overview
This project, developed by **Thangaraj**, focuses on predicting rainfall using machine learning techniques. The model aims to analyze various weather parameters to forecast the likelihood or amount of rainfall.  
The project is implemented in **Google Colab** and demonstrates the full data science workflow — from data preprocessing to model evaluation and optimization.

---

## 📊 Dataset
- **Source:** Dataset imported in Google Colab (can be updated with actual link if applicable)  
- **Type:** Weather dataset containing temperature, humidity, wind speed, and other atmospheric variables  
- **Target Variable:** Rainfall (amount or binary classification - Rain / No Rain)

---

## ⚙️ Project Workflow
1. **Importing Libraries**
2. **Data Loading and Inspection**
3. **Handling Missing Values**
4. **Exploratory Data Analysis (EDA)**
   - Univariate, Bivariate, and Multivariate Analysis  
   - Outlier detection and skewness visualization  
5. **Feature Engineering and Scaling**
6. **Model Building**
   - Linear Regression  
   - Lasso Regression  
   - Ridge Regression  
   - Decision Tree  
   - Random Forest  
7. **Model Evaluation**
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score  
8. **Hyperparameter Tuning using GridSearchCV**
9. **Model Comparison and Optimization**

---

## 📈 Model Evaluation Results
| Model | MAE | MSE | RMSE | R² Score |
|:------|:----|:----|:----|:----------|
| Linear Regression | 0.0086 | 0.00017 | 0.0130 | 0.9998 |
| Lasso Regression | 0.0095 | 0.00023 | 0.0153 | 0.9997 |
| Ridge Regression | 0.0086 | 0.00017 | 0.0131 | 0.9998 |

✅ The **Linear Regression** and **Ridge Regression** models provided the best performance with the highest R² score (~0.9998).

---

## 🚀 Future Enhancements
- Include more recent and diverse rainfall datasets  
- Test advanced ML models (Random Forest, Gradient Boosting, XGBoost)  
- Deploy model via **Streamlit** or **Flask Web App**  
- Add model interpretation using SHAP or LIME  

---

## 💻 How to Run in Google Colab
1. Open the notebook: **`Rainfall_prediction.ipynb`**
2. Upload the dataset to Colab environment
3. Run all cells sequentially
4. View model evaluation results and visualizations

---

## 🧠 Technologies Used
- **Python**
- **Google Colab**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 👨‍💻 Author
**Thangaraj M**  
📧 *thangarajk2002@gmail.com*  
🔗 [GitHub Profile](https://github.com/thangaraj-hunder)

---
⭐ *If you found this project helpful, please star this repository!*

