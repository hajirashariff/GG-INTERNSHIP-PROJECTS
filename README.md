# GG Internship Projects 🚀

Welcome to my AI-Powered Machine Learning Internship project portfolio! This repository showcases my hands-on implementation of machine learning models, exploratory data analysis (EDA), unsupervised clustering pipelines, and predictive regression systems. Each project is accompanied by a comprehensive technical assessment report.

---

## 📁 Repository File Structure

```text
GG-INTERNSHIP-PROJECTS/
├── README.md                               # Main repository overview and documentation
├── Project-1-IMDb-Movies/
│   ├── imdb_eda_analysis.ipynb             # Jupyter Notebook for IMDb data cleaning and EDA
│   └── P1-Assessment-HAJIRA_SHARIFF.pdf    # Final assessment report for IMDb analysis
├── Project-2-Customer-Segmentation/
│   ├── customer_segmentation.ipynb         # Jupyter Notebook for K-Means clustering and scaling
│   └── P2_Assessment_Hajira-Shariff.pdf    # Final assessment report for customer segmentation
└── Project-3-Uber-Fare-Prediction/
    ├── uber_fare_prediction.ipynb          # Jupyter Notebook for model benchmarking and tuning
    ├── uber_gradient_boosting_model.pkl    # Serialized final optimized Gradient Boosting model
    └── P3-Assessment-HAJIRA_SHARIFF.pdf    # Final assessment report for Uber fare prediction


```

---

## 🛠️ Projects Included

### 1. IMDb Top Movies Exploratory Data Analysis (EDA)

* **Description:** Performed exploratory data analysis on a comprehensive dataset of over 10,000 movies. Cleaned missing values, handled data types, and extracted genres and production company statistics.


* **Key Insights:** Visualized top-performing films by budget, revenue, and profit using Seaborn and Matplotlib, uncovering industry trends across decades.


* **Deliverable Report:** `P1-Assessment-HAJIRA_SHARIFF.pdf`

### 2. Customer Segmentation Using K-Means

* **Description:** Applied unsupervised learning algorithms (K-Means Clustering) on the Customer Personality dataset (`marketing_campaign.csv`) to group customer segments based on annual income and wine purchasing behavior.


* **Key Techniques:** Feature scaling via `StandardScaler`, determining optimal clusters using the **Elbow Method** and **Silhouette Scores**, and profiling cluster characteristics and purchase channel preferences.


* **Deliverable Report:** `P2_Assessment_Hajira-Shariff.pdf`

### 3. Predicting Uber Cab Fares Using Machine Learning

* **Description:** Built and optimized end-to-end regression machine learning pipelines to predict Uber trip fares based on temporal features, passenger count, and geodesic trip distances.
* **Key Techniques:** Calculated geodesic distances using `geopy`, benchmarked multiple regressors (Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and XGBoost), performed hyperparameter tuning via `RandomizedSearchCV`, and evaluated performance using MAE, RMSE, and $R^2$ metrics.
* **Deliverable Report:** `P3-Assessment-HAJIRA_SHARIFF.pdf`
* **Saved Artifact:** `uber_gradient_boosting_model.pkl`

---

## 💻 Tech Stack & Libraries

* **Languages:** Python
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **Geospatial Processing:** `geopy`
* **Data Visualization:** `matplotlib`, `seaborn`, `plotly`
* **Model Serialization:** `joblib`

```

```
