# Kaggle Spaceship Survival Prediction – Kaggle Competition

## 🚀 **Overview**  
This project addresses the Spaceship Titanic binary classification competition hosted on Kaggle. The task is to predict whether a passenger was transported to another dimension based on their personal, voyage, and spending information.

A complete machine learning pipeline was developed:

- ✅ Data exploration, cleaning, feature engineering, and preprocessing  
- ✅ Training with multiple models and hyperparameter tuning (GridSearchCV)  
- ✅ 5-Fold Cross-validation and final model deployment  

🎯 **Final Kaggle Score:** 0.80383 accuracy  
🏆 **Public Leaderboard Rank:** 378 out of 2189 teams

---

## 📊 Dataset
- **Source:** Kaggle Spaceship Titanic Dataset
- **Training Set:** 8693 rows × 14 columns
- **Test Set:** 4277 rows × 13 columns
- **Features:**  
  - HomePlanet, CryoSleep, Cabin, Destination, Age, VIP, RoomService, FoodCourt, ShoppingMall, Spa, VRDeck, Name
- **Target:**  
  - Transported (True = transported, False = not transported)

---

## 🧪 Key Tasks

- Exploratory Data Analysis (EDA) and missing value analysis
- Feature engineering:  
  - Splitting Cabin into Deck/Number/Side  
  - Creating GroupSize and AgeGroup  
  - Calculating TotalSpending and Spend_per_Age
- Handling categorical variables using One-Hot Encoding
- Feature scaling with MinMaxScaler
- Model training with multiple algorithms
- Hyperparameter tuning with GridSearchCV
- 5-Fold Cross-Validation and model validation
- Preparing final Kaggle submission

---

## 🔍 Key Steps

### Data Cleaning

- Filling missing values in Age, CryoSleep, VIP, HomePlanet, Destination
- Handling missing Cabin values and missing spending amounts
- Dropping irrelevant columns like Name and Group

### Exploratory Data Analysis (EDA)

- Visualizing distributions and outliers
- Correlation heatmaps
- Survival rates across different planets, decks, and spending patterns

### Modeling

- Logistic Regression
- Random Forest Classifier
- Decision Tree
- Gradient Boosting
- AdaBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost
- LightGBM

### Evaluation

- Accuracy, Precision, Recall, F1-Score
- Cross-validation with 5 folds
- Confusion Matrix visualization
- Feature importance analysis

### Submission

- Preparing CSV submission file with PassengerId and Transported (True/False)

---

## 🔧 Technologies Used

- Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM)
- Jupyter Notebook
- Kaggle Kernels and APIs
- Git & GitHub
- Joblib (for saving final model and scaler)

---

## 🧠 What I Learned

- How advanced feature engineering (GroupSize, TotalSpending) can impact model performance
- The importance of hyperparameter tuning and validation
- Handling categorical and numeric data correctly for machine learning
- The benefits of ensembling models to push Kaggle scores higher
- Full ML pipeline deployment for reproducible submissions

---

## 👏 Author

**Reza Zare** — Complete ML pipeline designed, implemented, tuned, and deployed from scratch.

---

## 📎 Resources

- [Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic)
- Spaceship Titanic Data Dictionary

---

## 📎 Credits

Dataset sourced from Kaggle for educational and competition purposes.  
All rights to the original dataset belong to Kaggle and respective contributors.

---
