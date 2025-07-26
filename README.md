## 📊 Marketing Campaign Analysis (Machine Learning Model)

This project applies machine learning techniques to analyze and predict customer responses to marketing campaigns using a cleaned dataset. It demonstrates end-to-end workflow including data preprocessing, feature engineering, model training, and evaluation.

---

### 📁 Project Structure

- `ML_Marketing_Compaign.ipynb`: Main notebook containing all steps from data loading to model evaluation.
- `cleaned_marketing_data.csv`: Preprocessed dataset used for training and testing.

---

### 🧠 Key Features

- **Exploratory Data Analysis (EDA)**: Summary statistics and distribution insights.
- **Preprocessing Pipeline**:
  - Standardization of numeric features
  - One-hot encoding of categorical features
  - ColumnTransformer for unified preprocessing
- **Modeling**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- **Evaluation**:
  - Accuracy scores via 5-fold cross-validation
  - Comparison of model performance

---

### 📈 Model Performance

| Model              | Accuracy (Mean ± Std) |
|-------------------|------------------------|
| Logistic Regression | 0.8714 ± 0.0397        |
| Random Forest       | 0.7179 ± 0.2665        |
| Gradient Boosting   | 0.5835 ± 0.2398        |

---

### 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ML_Marketing_Campaign.git
   cd ML_Marketing_Campaign
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook ML_Marketing_Compaign.ipynb
   ```

---

### 🛠 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Pipeline, ColumnTransformer, Classifiers)
- Jupyter Notebook

---

### 📬 Contact

For questions or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/vincent-napolean-susai/) or open an issue.

---

## 🤖 Multimodel Classification

This project demonstrates a multi-output classification pipeline using multiple machine learning models to predict several customer attributes simultaneously. It showcases scalable training and deployment of models for each target variable using `scikit-learn` and `joblib`.

---

### 📂 Project Overview

- **Notebook**: `ML_Multimodel.ipynb`
- **Dataset**: `cleaned_marketing_data.csv`
- **Targets**: Education, Marital Status, Country, Age Group
- **Models Used**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting

---

### 🧠 Key Features

- **Multi-Target Learning**: Trains separate models for each target column.
- **Pipeline Integration**: Uses `Pipeline` and `StandardScaler` for consistent preprocessing.
- **Model Serialization**: Saves each trained model using `joblib` for future inference.
- **Modular Design**: Easily extendable to other targets or models.

---

### 🛠 Technologies

- Python (Pandas, NumPy)
- Scikit-learn (MultiOutputClassifier, Pipelines, Classifiers)
- Joblib (Model persistence)
- Jupyter Notebook

---

### 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ML_Multimodel.git
   cd ML_Multimodel
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook ML_Multimodel.ipynb
   ```

---

### 📦 Output Models

Each model is saved with the format:
```
<model_name>_<target_column>_model.joblib
```

Example:
- `logistic_regression_Education_model.joblib`
- `random_forest_Country_model.joblib`

---

### 📬 Contact

For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/your-profile) or open an issue.




