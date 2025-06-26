# 🧠 Linear Regression on Housing Dataset (Custom)

## 📌 Objective
To implement and analyze **Simple** and **Multiple Linear Regression** using a housing dataset to predict `price` based on various features such as location, number of bedrooms, size, and furnishing status.

---

## 📁 Dataset
- **Filename:** `Housing.csv`
- **Source:** Provided locally in `sample_data/` (used in Colab/Notebook)
- **Target Variable:** `price`
- **Features:**
  - `area` (in sq. ft.)
  - `bedrooms`
  - `bathrooms`
  - `stories`
  - `mainroad`, `guestroom`, `basement`, etc. (categorical)
  - `furnishingstatus` (semi-furnished, furnished, unfurnished)

---

## 🛠 Tools & Libraries Used
- Python
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (model building and evaluation)

---

## 🔄 Workflow

### 1. Data Preprocessing
- Checked for missing values
- Converted categorical features to numerical using one-hot encoding
- Verified dataset structure using `.info()` and `.describe()`

### 2. Simple Linear Regression
- Used a single feature (e.g., `area`) to predict `price`
- Visualized regression line using scatter plot
- Evaluated using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score

### 3. Multiple Linear Regression
- Used all cleaned and encoded features to predict `price`
- Displayed top influencing features using coefficients
- Compared performance with simple regression

### 4. Visualization
- Plotted regression predictions
- Visualized residual distribution

---

## 📊 Results Summary

- ✅ **Multiple Regression** yielded better performance due to richer feature use.
- 🔍 Residuals followed roughly a normal distribution, indicating good model fit.

---

## 📂 Folder Structure
├── linear_regression.ipynb 

├── Housing.csv 

├── README.md 

## 🧠 Key Learnings
- How to preprocess real-world tabular data
- Implementing linear regression from scratch using `scikit-learn`
- Importance of feature encoding and selection
- Using metrics (MAE, MSE, R²) to evaluate model effectiveness
- Understanding how model coefficients reflect feature impact

  ## Author
  Shweta Yenaji
