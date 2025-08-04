# 🚢 Titanic Dataset: Data Cleaning & Preprocessing

This project covers the essential steps in preparing raw data for machine learning using the Titanic dataset. The main focus is on cleaning, handling missing data, encoding categorical variables, feature scaling, and outlier detection.

---

## 📌 Objective

- Understand and clean raw data
- Handle missing values appropriately
- Convert categorical features to numerical
- Normalize/standardize numerical features
- Visualize and remove outliers

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

---

## 📂 Dataset

Dataset used: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

File: `titanic.csv`

---

## 🧪 Preprocessing Steps

### 1. Import Dataset & Explore Basic Info

- Loaded dataset using Pandas
- Explored structure with `.head()`, `.info()`, and `.describe()`
- Checked for null values and data types

### 2. Handle Missing Values

- Filled missing `Age` values using **median**
- Filled missing `Embarked` values using **mode**
- Dropped `Cabin` column due to high missing rate

### 3. Encode Categorical Features

- Converted `Sex` to 0 (male) and 1 (female)
- One-hot encoded `Embarked` using `get_dummies()`

### 4. Normalize/Standardize Numerical Features

- Used `StandardScaler` to standardize `Age` and `Fare`
- Verified that scaled features have mean ≈ 0 and std ≈ 1

### 5. Visualize and Remove Outliers

- Used boxplots (`sns.boxplot`) to detect outliers
- Removed outliers from `Age` and `Fare` using the IQR method

---

## 📈 What's Next (Optional Future Work)

- Train machine learning models like Logistic Regression, Random Forest
- Improve prediction with class balancing, feature engineering, tuning

---

## 🧑‍💻 Author

Mukesh Sunku  
[GitHub](https://github.com/your-username)

---

## 📄 License

This project is released under the [MIT License](LICENSE).
