# Car-Price-Prediction
This project aims to predict car selling prices using machine learning models trained on a Kaggle dataset.
## 📊 Project Workflow

### 1. Data Loading
- Source: [Kaggle - Car Price Dataset](https://www.kaggle.com/)
- Data is loaded using Pandas from a relative path.

### 2. Exploratory Data Analysis (EDA)
- Summary statistics
- Visualization of relationships between:
  - Year and Selling Price
  - Present Price and Selling Price
  - Kms Driven and Selling Price
  - Fuel Type and Selling Price
  - Seller Type and Selling Price
- Outlier detection

### 3. Data Preprocessing
- Categorical variables encoded using One-Hot Encoding
- Features (`x`) separated from target (`y`)

### 4. Modeling
- Models used:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Evaluation metrics:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

### 5. Model Selection & Saving
- The best model based on R² score is saved as .pkl using joblib.

### 6. Visualization
- Bar chart comparing R² scores of models

## 🛠 Technologies
- Python
- Pandas, NumPy, Matplotlib, Scikit-learn, Joblib
- Jupyter Notebook (optional)
