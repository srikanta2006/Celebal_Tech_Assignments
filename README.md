# Celebal Tech Assignments

Welcome to my repository for the Celebal Tech program! This repository contains all my weekly course notes, codebase implementations, and assignment solutions, documenting my progression through data science, machine learning, and advanced analytics concepts.

## 👤 Author
**Srikanta**

## 🛠️ Technologies & Libraries Used
* **Language:** Python
* **Data Manipulation:** NumPy, Pandas
* **Machine Learning:** Scikit-Learn
* **Time Series & Forecasting:** Statsmodels, Prophet
* **Data Visualization:** Matplotlib, Seaborn

---

## 📚 Curriculum & Progression

### Week 1: Foundations of Data Science & Mathematics
This week focused on building a strong mathematical and programming foundation required for robust data modeling and analysis. 

**Programming Essentials**
* Python Crash Course
* NumPy (Numerical Python)
* Pandas (Data Manipulation)

**Linear Algebra**
* Vectors and Matrices as Data
* Matrix Operations in Practice
* Eigenvalues and Eigenvectors
* Dimensionality Reduction Basics

**Probability & Statistics**
* Stats and Its Types
* Hypothesis Testing Basics
* Distributions in the Wild
* Distribution and Stationarity Testing
* Bayes' Theorem Intuition
* The Central Limit Theorem (CLT)

**Machine Learning Fundamentals**
* Core Concepts
* Error Metrics and Graphical Intuition
* Model Monitoring Basics

### Week 2: Applied Machine Learning & Time Series
This week transitioned into practical machine learning pipelines, regression techniques, and temporal forecasting.

**Machine Learning Core**
* Types of ML & The ML Pipeline
* Bias-Variance Tradeoff
* Overfitting and Underfitting

**Data Preparation & Feature Engineering**
* Data Cleaning & Exploratory Data Analysis (EDA)
* Encoding Techniques & Feature Scaling
* Feature Engineering & Pipelines
* Data Leakage Prevention

**Regression Algorithms**
* Linear Regression
* Ridge Regression (L2)
* Lasso Regression (L1)

**Model Evaluation & Tuning**
* Evaluation Metrics
* Cross Validation
* Hyperparameter Tuning

**Time Series Analysis**
* Time Series Components & Stationarity
* Lag Features & Rolling Statistics
* Chronological Splitting
* Forecasting Methodologies

### Week 3: Classification & Clustering
This week covered the full spectrum of supervised classification algorithms, ensemble methods, and unsupervised clustering techniques.

**Classification Algorithms**
* Logistic Regression
* Naive Bayes
* K-Nearest Neighbors (KNN)
* Support Vector Machines (SVM)
* Decision Tree

**Ensemble Methods**
* Random Forest & Feature Importance
* AdaBoost
* Gradient Boosting
* XGBoost
* LightGBM
* Stacking

**Model Evaluation**
* Evaluation Metrics (Accuracy, Precision, Recall, F1, ROC-AUC)

**Unsupervised Learning & Clustering**
* K-Means Clustering
* K-Medoids
* DBSCAN
* Hierarchical Clustering
* Cluster Evaluation (Silhouette Score, Inertia)
---

## 💻 Assignments

### Week 1
* **Foundational Analytics:** *Complete foundational exercises on Python, Linear Algebra, Statistics & Probability.*
* **Link to code:** [Week 1 Assignment File](https://github.com/srikanta2006/Celebal_Tech_Assignments/blob/main/week1_srikanta.ipynb)

### Week 2
* **End-to-End ML Pipeline (Tesla Production & Deliveries Dataset)**
  * **Description:** Designed and implemented a complete machine learning pipeline on global sales/price data. The project bridges standard regression and time-series forecasting. It features rigorous data auditing, temporal formatting, lag/rolling feature engineering, and a strict chronological train-test split. 
  * **Models Deployed:** Baseline Linear Regression, Hyperparameter-tuned Random Forest (using `TimeSeriesSplit`), SARIMA, and Meta Prophet.
  * **Link to code:** [Week 2 Assignment File](https://github.com/srikanta2006/Celebal_Tech_Assignments/blob/main/week2_srikanta.ipynb)

### Week 3
* **End-to-End Customer Intelligence System (Country Data Dataset)**
  * **Description:** Built a complete end-to-end machine learning pipeline on global socio-economic data. The project bridges unsupervised clustering and supervised classification. It features thorough data auditing, IQR-based outlier capping, StandardScaler preprocessing, and PCA-based dimensionality reduction for visualization. Cluster labels derived from K-Means are used as targets to enable downstream classification, creating a cohesive intelligence pipeline.
  * **Models Deployed:** K-Means Clustering (Elbow + Silhouette tuning), DBSCAN (K-Distance eps tuning), Baseline Random Forest, Baseline XGBoost, Hyperparameter-tuned Random Forest & XGBoost (using `GridSearchCV`), and Soft Voting Ensemble (RF + XGBoost).
  * **Link to code:** [Week 3 Assignment File](https://github.com/srikanta2006/Celebal_Tech_Assignments/blob/main/week3_srikanta.ipynb)
---
