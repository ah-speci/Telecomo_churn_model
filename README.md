

# 📊 Telecom Customer Churn Prediction

A Machine Learning project that predicts whether a telecom customer is likely to churn based on customer demographics, account information, and subscribed services.

The project follows a complete end-to-end machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

---

# 📌 Project Objective

Customer churn is one of the biggest challenges faced by telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones.

The objective of this project is to build a machine learning model that accurately predicts customer churn, enabling telecom companies to identify customers at risk of leaving and take proactive retention measures.

---

# 📂 Dataset

* **Dataset:** IBM Telco Customer Churn Dataset
* **Total Customers:** 7,043
* **Features:** 21
* **Target Variable:** `Churn`

The dataset contains customer demographics, service subscriptions, contract details, billing information, and payment methods.

---

# 🛠️ Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Final Model Evaluation
      │
      ▼
Prediction
```


---

# 📊 Exploratory Data Analysis

The following analyses were performed:

* Churn distribution
* Gender analysis
* Senior citizen analysis
* Partner and dependent analysis
* Contract type analysis
* Internet service analysis
* Payment method analysis
* Monthly charges distribution
* Total charges distribution
* Tenure distribution
* Correlation heatmap
* Feature relationships with churn

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Missing value handling
* Data type conversion
* Label Encoding
* One-Hot Encoding
* Feature Scaling
* Train-Test Split

---

# 🤖 Machine Learning Models

The following machine learning algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest


Model performance was compared using multiple evaluation metrics, and the best-performing model was selected.

---

# 🔧 Hyperparameter Tuning

Hyperparameter optimization was performed using both **GridSearchCV** and **Optuna**.

### GridSearchCV

* Exhaustive search over predefined hyperparameter combinations.
* Used to establish strong baseline tuned models.

### Optuna

* Bayesian optimization framework.
* Efficiently explored the hyperparameter search space.
* Improved model performance while requiring fewer trials than exhaustive search.

The best hyperparameters obtained from both approaches were compared, and the highest-performing model was selected as the final model.

---

# 📈 Model Evaluation

The final model was evaluated using the following metrics:

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **0.8012** |
| Precision | **0.6566** |
| Recall    | **0.5267** |
| F1 Score  | **0.5845** |
| ROC AUC   | **0.8429** |
---

# 📦 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Optuna
* Jupyter Notebook

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/ah-spec/Telecom-churn-model.git
```

Move into the project directory:

```bash
cd Telecom-churn-model
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# ▶️ Running the Project

Execute the notebooks in the following order:

1. Data Analysis
2. Data Preprocessing
3. Model Training
4. Model Tuning
5. Prediction

---

# 📌 Future Improvements

* Deploy the model using Flask or FastAPI
* Develop a web application for predictions
* Explain model predictions using SHAP values
* Build an end-to-end ML pipeline
* Automate model retraining
* Add model monitoring and logging

---

# 👨‍💻 Author

**Sahil Chandra**

GitHub: https://github.com/ah-spec

---

# 📄 License

This project is intended for educational purposes and portfolio demonstration.

