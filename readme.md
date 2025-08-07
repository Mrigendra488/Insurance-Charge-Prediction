
## 🔍 Problem Statement

Health insurance companies often charge premiums based on customer profiles. Our goal is to predict medical charges using features such as age, BMI, and lifestyle choices.

## 📊 Dataset Description

- **age**: Age of primary beneficiary
- **sex**: Gender of the beneficiary
- **bmi**: Body mass index
- **children**: Number of children covered by health insurance
- **smoker**: Smoking status
- **region**: Residential area
- **charges**: Medical insurance charges (target variable)

## 🧪 Workflow

1. **Data Loading**
2. **Exploratory Data Analysis**
3. **Preprocessing**
    - Handling categorical variables
    - Feature scaling
4. **Modeling**
    - Linear Regression
    - Ridge and Lasso regularization
5. **Model Evaluation**
    - R² and Adjusted R²
    - Train/Test split comparison
    - Overfitting/Underfitting check

## 🧠 Results

- **Train R²**: 0.74
- **Test R²**: 0.806
- **Adjusted R²**: 0.801

These scores indicate a well-generalized model with minimal overfitting.

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📌 Key Learnings

- Importance of feature encoding and scaling
- How to interpret R² and Adjusted R²
- Detecting overfitting using train/test performance
- Using Ridge and Lasso for regularization

## 📚 Future Improvements

- Try non-linear models (Random Forest, Gradient Boosting)
- Hyperparameter tuning using GridSearchCV
- Deploy model using Streamlit or Flask

## 👤 Author

Mrigendra Pratap Singh

---

If you found this project helpful, give it a ⭐️ on GitHub!
