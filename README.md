# ✈️ Air Tickets ML Project

This project analyzes and predicts flight ticket prices using real Expedia flight data.  
It is built to practice and demonstrate data science and machine learning skills,  
with a focus on **feature engineering, model comparison, hyperparameter tuning,  
and experiment tracking**.

---

## 📂 Project Structure
air-tickets-ml/
│
├── data/ # raw and processed datasets (not pushed to GitHub if large)

├── notebooks/ # Jupyter notebooks for EDA, modeling, tuning

│ ├── 01_eda.ipynb
│ ├── 02_feature_engineering.ipynb
│ ├── 03_modeling.ipynb
│ └── 04_tuning.ipynb

├── src/ # reusable Python scripts

├── README.md # project overview

└── requirements.txt # Python dependencies


---

## 🚀 Project Goals
1. **EDA**: Explore pricing patterns, routes, seasonal effects.
2. **Feature Engineering**: Create booking lead time, departure hour, route distance, etc.
3. **Modeling**: Compare baseline models with Gradient Boosting (LightGBM, XGBoost, CatBoost).
4. **Hyperparameter Tuning**: Use Optuna for optimization.
5. **Experiment Tracking**: Log results with MLflow.
6. **Interpretation**: Explain feature importance (e.g., SHAP values).
7. **Presentation**: Deliver clear visual insights.

---

## 🛠️ Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn
- LightGBM / CatBoost / XGBoost
- Optuna (hyperparameter tuning)
- MLflow (experiment tracking)
- Jupyter Notebooks

---

## 📊 Dataset
Expedia flight prices dataset (April–October 2022), available on [Kaggle](https://www.kaggle.com/datasets/dilwong/flightprices).

---

## 📈 Expected Outcomes
- Predict flight ticket prices with high accuracy.
- Identify the most important features affecting ticket prices.
- Build a shareable project portfolio demonstrating ML workflow.

---

## 👤 Author
- **Ilias Outras**  
  Data Scientist | Civil Engineer | Passion for ML in Travel Industry
