# 🔥 ML Project - Calorie Burnt Prediction  

## 🚀 Overview  
This **Machine Learning project** focuses on **Calories Burnt Prediction** using the **XGBoost Regressor** algorithm.  
The model predicts the number of calories burned during physical activity based on inputs such as **Gender, Age, Height, Weight, Duration, Heart Rate, and Body Temperature**.  

Extensive **Exploratory Data Analysis (EDA)** was performed, including the **distribution of Age and Height**, and a **correlation heatmap** was created to identify **positive and negative correlations** among features.  

The model effectively learns complex relationships between physiological data and calorie expenditure, demonstrating how ML can be applied in **fitness tracking and health analytics** for personalized insights.  

---

## 🔍 About the Project  
This project applies **supervised regression techniques** to predict calories burned during workouts or physical activity sessions.  
It uses **physiological and biometric attributes** to estimate energy expenditure, providing insights for **fitness tracking**, **diet planning**, and **health optimization**.  
The project showcases how **machine learning** enhances **personalized health monitoring systems** and supports wellness applications.  

---

## 🧠 Model Architecture  
The project uses **XGBoost Regressor**, a powerful ensemble learning algorithm that combines decision trees using gradient boosting for superior predictive accuracy.  

* **Algorithm:** XGBoost Regressor  
* **Problem Type:** Regression  
* **Evaluation Metrics:** R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)  

---

## 🧾 Dataset Description  
The dataset contains biometric and activity-related features used to predict calorie burn:  

| Feature | Description |
|----------|-------------|
| **Gender** | Male or Female indicator |
| **Age** | Age of the individual (in years) |
| **Height** | Height in centimeters |
| **Weight** | Weight in kilograms |
| **Duration** | Duration of the activity (in minutes) |
| **Heart Rate** | Average heart rate during activity |
| **Body Temperature** | Temperature recorded during workout |
| **Calories** | Target variable — calories burned |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computation  
* **Pandas** – Data manipulation and preprocessing  
* **Matplotlib / Seaborn** – Data visualization and correlation analysis  
* **Scikit-learn** – Data splitting and evaluation metrics  
* **XGBoost** – Regression model for calorie prediction  

---

## 🚀 Features  
* Predicts **calories burned** using physiological data  
* Performs detailed **EDA** with distributions and correlation heatmaps  
* Utilizes **XGBoost Regressor** for high prediction accuracy  
* Helps in **fitness monitoring** and **personalized health analytics**  
* Demonstrates ML application in **sports science and wearable tech**  

---

## 📊 Results  
The **XGBoost Regressor** model achieved strong performance with high correlation between actual and predicted calorie values.  
The EDA results identified that **Heart Rate**, **Duration**, and **Weight** are major contributors to calorie expenditure.  

---

## 📁 Repository Structure  

```
📦 ML-Projects-Calorie-Burnt-Prediction
│
├── Calories_Burnt_Prediction.ipynb                                 # Model implementation
├── calories.csv                                                    # Dataset used for training and testing
├── exercise.csv                                                    # Additional dataset
└── README.md                                                       # Project documentation
```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Calorie-Burnt-Prediction.git
   cd ML-Projects-Calorie-Burnt-Prediction


2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Calorie_Burnt_Prediction.ipynb
   ```

4. **Execute all cells to train, test, and visualize model results.**

---

## 📈 Future Improvements

* Add hyperparameter tuning using GridSearchCV for optimization

* Build a Streamlit dashboard for real-time calorie prediction

* Integrate wearable device data for enhanced model accuracy

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
