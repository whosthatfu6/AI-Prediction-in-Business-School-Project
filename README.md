# AI-Prediction-in-Business-School-Project
# 📊 Systematic Machine Learning & Deep Learning Portfolio for Business Analytics

This portfolio showcases a structured progression of data science techniques applied to various business intelligence, predictive modeling, and analytics challenges. It spans from exploratory data analysis (EDA) and unsupervised clustering to classical machine learning and deep neural networks (ANN) using Google Colab.

---

## 🔍 Portfolio Overview

### 🏢 HR Employee Churn Analysis (Level 1: Pure EDA)
* **Dataset File:** `HR_left_chi.csv`
* **Key Tasks:** 
  * Filtering high-impact factors using a correlation matrix (correlation coefficients absolute value > 0.1).
  * Feature encoding text variables (departments, salary levels) using `LabelEncoder`.
  * Multi-dimensional trend exploration with Seaborn's `pairplot` and `heatmap`.
  * Visualizing satisfaction rates vs. employee tenure and churning ratios using Matplotlib pie charts.

### 🛍️ Mall Customer Segmentation (Level 2: Unsupervised Clustering)
* **Dataset File:** `Mall_Customers_chi.csv`
* **Key Tasks:**
  * Segmenting anonymous retail customer groups using **K-Means clustering** (`n_clusters=5`, `random_state=200`).
  * Identifying key buyer personas based on age, annual income, and spending scores.
  * Real-time prediction mapping to assign new potential shoppers into the correct customer segment.

### 🚢 Titanic Survival & Patient Drug Prescription (Level 3: Classical Supervised Classification)
* **Dataset Files:** `titanic_pre-chi.xlsx`, `drug200-chi.csv`
* **Key Tasks:**
  * Comparing manual data mapping (e.g., class mapping on Titanic) against automated preprocessing with `LabelEncoder`.
  * Implementing **K-Nearest Neighbors (KNN)** classification for binary (survival) and multi-class (drug type) target variables.
  * Diagnosing model predictions using **Confusion Matrix Displays** and classification reports.
  * Rigorously evaluating and mitigating model **overfitting** by comparing Train vs. Test accuracy scores.

### 🍷 Wine Variety Classification (Level 4: Multi-Model Evaluation)
* **Dataset File:** `wine-chi-1.csv`
* **Key Tasks:**
  * Conducting statistical profiling of chemical indicators using boxplots and linear regressions.
  * Benchmarking and comparing three classic classification algorithms: **KNN**, **Decision Tree**, and **Random Forest**.
  * Optimizing accuracy on test splits to identify the best overall classifier.

### 📈 Cyclical Commercial Trend Fitting (Level 5: Deep Learning Regression)
* **Dataset File:** `curve-3.csv`
* **Key Tasks:**
  * Modeling highly non-linear, cyclical business fluctuations.
  * Evaluating the limitations of high-degree **Polynomial Regression** (15th, 20th, 30th degree) regarding underfitting and wave distortions.
  * Designing a **Keras Artificial Neural Network (ANN) Regressor** with multiple hidden layers (ReLU activation, Adam optimizer, MSE loss) for robust wave trend fitting.

### 🧪 Deep Learning Multi-Class Prediction (Level 6: Advanced Neural Networks)
* **Dataset File:** `wine-chi-4.csv`
* **Key Tasks:**
  * Implementing **One-Hot Encoding** on target categorical labels.
  * Training a multi-class Keras Sequential Neural Network Classifier.
  * Tracking training progress (Loss and Accuracy) across epochs using Pandas to plot **training history curves** to verify convergence and prevent overfitting.
  * Deploying the trained network to classify unseen wine samples.

---

## 🛠️ Tools & Libraries Used

* **Python** – Core programming language for data manipulation
* **Pandas & NumPy** – Structured data processing, matrix operations, and feature transformations
* **Scikit-learn** – Machine learning pipelines, model training, encoders, and evaluation metrics
* **TensorFlow / Keras** – Designing, compiling, and training Artificial Neural Networks (ANN)
* **Matplotlib & Seaborn** – Professional statistical plotting, correlation heatmaps, pairplots, and boxplots
* **Google Colab** – Interactive cloud-based execution environment
