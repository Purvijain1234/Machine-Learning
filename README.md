<div align="center">

# 🤖 Machine Learning - My Learning Journey

**A structured, hands-on repository documenting my journey through Machine Learning — from data preprocessing to end-to-end deployed projects.**

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Actively%20Learning-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## 📌 About This Repository

This repository is my personal **Machine Learning knowledge base** — a growing collection of notebooks, notes, and mini-projects covering everything from **data preprocessing** to **full end-to-end ML pipelines**. Each topic includes a Jupyter notebook, a visual explanation (`.png`), and a short `README.md` explaining the concept.

> 💡 Goal: Build strong ML fundamentals through consistent, hands-on practice — one topic at a time.

---

## 🗺️ Roadmap

<div align="center">
<img src="assets/roadmap.png" alt="Learning Roadmap" width="80%">
</div>

---

## ✅ Learning Progress Tracker

> Check items off as you complete them — GitHub renders these as clickable checkboxes!

- [x] 01. Data Preprocessing
- [ ] 02. Feature Engineering
- [ ] 03. Statistics for ML
- [ ] 04. Probability for ML
- [ ] 05. Linear Algebra for ML
- [ ] 06. Supervised Learning
- [ ] 07. Unsupervised Learning
- [ ] 08. Model Evaluation
- [ ] 09. Hyperparameter Tuning
- [ ] 10. End-to-End Projects

---

## 📖 Table of Contents

<details>
<summary><b>Click to expand full contents</b></summary>

- [01. Data Preprocessing](#01-data-preprocessing)
- [02. Feature Engineering](#02-feature-engineering)
- [03. Statistics for ML](#03-statistics-for-ml)
- [04. Probability for ML](#04-probability-for-ml)
- [05. Linear Algebra for ML](#05-linear-algebra-for-ml)
- [06. Supervised Learning](#06-supervised-learning)
- [07. Unsupervised Learning](#07-unsupervised-learning)
- [08. Model Evaluation](#08-model-evaluation)
- [09. Hyperparameter Tuning](#09-hyperparameter-tuning)
- [10. End-to-End Projects](#10-end-to-end-projects)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

</details>

---

## 01. Data Preprocessing

<details>
<summary><b>📁 Click to expand — Cleaning and preparing raw data for modeling</b></summary>

<br>

Covers the essential first step of any ML pipeline: turning messy, real-world data into a clean dataset ready for analysis.

- [x] **Missing Values** — Techniques to detect and handle null/missing entries (mean/median/mode imputation, dropping, interpolation).
- [ ] **Duplicate Data** — Identifying and removing duplicate records to avoid data leakage and bias.
- [ ] **Handling Outliers** — Detecting anomalies using IQR, Z-score, and visual methods, and deciding how to treat them.
- [ ] **Encoding Categorical Data** — Converting categorical variables using One-Hot, Label, and Ordinal encoding.
- [ ] **Feature Scaling** — Standardization and Normalization to bring features onto a comparable scale.
- [ ] **Train Test Split** — Properly splitting data to evaluate model generalization.
- [ ] **Imbalanced Data (SMOTE)** — Balancing skewed class distributions using oversampling techniques.
- [ ] **Data Transformation** — Log, power, and other transformations to fix skewed distributions.

📂 `01_Data_Preprocessing/`

</details>

---

## 02. Feature Engineering

<details>
<summary><b>📁 Click to expand — Crafting better features to boost model performance</b></summary>

<br>

The art of transforming raw variables into meaningful inputs that help models learn better.

- [ ] **Feature Selection** — Choosing the most relevant features using filter, wrapper, and embedded methods.
- [ ] **Feature Extraction** — Deriving new features from existing raw data.
- [ ] **PCA** — Reducing dimensionality while preserving variance.
- [ ] **LDA** — Supervised dimensionality reduction for class separability.
- [ ] **Polynomial Features** — Capturing non-linear relationships via feature expansion.
- [ ] **Date/Time Features** — Extracting day, month, season, and cyclic patterns from timestamps.
- [ ] **Text Features** — Converting text into numerical features (TF-IDF, Bag of Words).
- [ ] **Feature Creation** — Domain-driven creation of new, informative features.
- [ ] **Dimensionality Reduction** — Overview of techniques to reduce feature space efficiently.

📂 `02_Feature_Engineering/`

</details>

---

## 03. Statistics for ML

<details>
<summary><b>📁 Click to expand — The statistical backbone behind every ML algorithm</b></summary>

<br>

Statistical concepts required to understand model behavior, data distributions, and hypothesis-driven decisions.

- [ ] **Mean, Median, Mode** — Measures of central tendency.
- [ ] **Variance** — Spread of data around the mean.
- [ ] **Standard Deviation** — Measuring data dispersion.
- [ ] **Covariance** — Relationship direction between two variables.
- [ ] **Correlation** — Strength and direction of linear relationships.
- [ ] **Skewness** — Asymmetry in data distribution.
- [ ] **Kurtosis** — Peakedness/tailedness of a distribution.
- [ ] **Quartiles & IQR** — Data spread and outlier boundaries.
- [ ] **Confidence Interval** — Estimating population parameters with certainty ranges.
- [ ] **Hypothesis Testing** — Statistical validation of assumptions.
- [ ] **p-Value** — Significance testing in decision-making.
- [ ] **Type I & Type II Error** — Understanding false positives/negatives.
- [ ] **A/B Testing** — Comparing two variants to measure impact.

📂 `03_Statistics_for_ML/`

</details>

---

## 04. Probability for ML

<details>
<summary><b>📁 Click to expand — Understanding uncertainty and randomness in data</b></summary>

<br>

Probability theory that powers Naive Bayes, generative models, and uncertainty estimation.

- [ ] **Probability Basics** — Foundational rules and axioms.
- [ ] **Conditional Probability** — Probability of an event given another has occurred.
- [ ] **Bayes' Theorem** — Updating beliefs using new evidence.
- [ ] **Random Variables** — Discrete vs continuous variables.
- [ ] **PMF / PDF / CDF** — Probability functions for distributions.
- [ ] **Bernoulli Distribution** — Binary outcome modeling.
- [ ] **Binomial Distribution** — Repeated binary trials.
- [ ] **Poisson Distribution** — Modeling rare event occurrences.
- [ ] **Uniform Distribution** — Equal probability outcomes.
- [ ] **Normal Distribution** — The bell curve and its significance.
- [ ] **Exponential Distribution** — Modeling time between events.
- [ ] **Central Limit Theorem** — Why sample means approximate normality.

📂 `04_Probability_for_ML/`

</details>

---

## 05. Linear Algebra for ML

<details>
<summary><b>📁 Click to expand — The mathematical language of machine learning</b></summary>

<br>

Core linear algebra concepts that power everything from neural networks to PCA.

- [ ] **Scalars** — Single numerical values.
- [ ] **Vectors** — Ordered arrays representing data points.
- [ ] **Matrices** — 2D data structures for transformations.
- [ ] **Matrix Multiplication** — Combining matrices for transformations.
- [ ] **Dot Product** — Measuring vector similarity/projection.
- [ ] **Cross Product** — Vector operations in 3D space.
- [ ] **Transpose** — Flipping rows and columns.
- [ ] **Determinant** — Scaling factor of a transformation.
- [ ] **Rank** — Number of independent dimensions.
- [ ] **Inverse** — Reversing a matrix transformation.
- [ ] **Eigenvalues** — Scalars indicating transformation stretch.
- [ ] **Eigenvectors** — Directions unchanged by a transformation.
- [ ] **Norms** — Measuring vector magnitude/length.
- [ ] **Orthogonality** — Perpendicularity between vectors.
- [ ] **Singular Value Decomposition** — Factorizing matrices for dimensionality reduction.

📂 `05_Linear_Algebra_for_ML/`

</details>

---

## 06. Supervised Learning

<details>
<summary><b>📁 Click to expand — Learning from labeled data</b></summary>

<br>

Algorithms that learn a mapping from inputs to known outputs — the most common type of ML.

### 📈 Regression
- [ ] Linear Regression
- [ ] Polynomial Regression
- [ ] Ridge Regression
- [ ] Lasso Regression
- [ ] ElasticNet
- [ ] Decision Tree Regression
- [ ] Random Forest Regression
- [ ] Support Vector Regression
- [ ] KNN Regression
- [ ] Gradient Boosting
- [ ] AdaBoost
- [ ] XGBoost

### 🏷️ Classification
- [ ] Logistic Regression
- [ ] KNN
- [ ] Naive Bayes
- [ ] Decision Tree
- [ ] Random Forest
- [ ] SVM
- [ ] Gradient Boosting
- [ ] AdaBoost
- [ ] XGBoost
- [ ] LightGBM
- [ ] CatBoost
- [ ] Extra Trees

📂 `06_Supervised_Learning/`

</details>

---

## 07. Unsupervised Learning

<details>
<summary><b>📁 Click to expand — Finding hidden patterns in unlabeled data</b></summary>

<br>

Techniques to discover structure, clusters, and patterns without predefined labels.

- [ ] **KMeans** — Centroid-based clustering.
- [ ] **Hierarchical Clustering** — Tree-based nested clustering.
- [ ] **DBSCAN** — Density-based clustering for arbitrary shapes.
- [ ] **Gaussian Mixture Model** — Probabilistic soft clustering.
- [ ] **PCA** — Dimensionality reduction via variance maximization.
- [ ] **t-SNE** — Non-linear visualization of high-dimensional data.
- [ ] **UMAP** — Fast, scalable non-linear dimensionality reduction.
- [ ] **Apriori** — Association rule mining.
- [ ] **FP-Growth** — Efficient frequent pattern mining.
- [ ] **Isolation Forest** — Anomaly detection via isolation.
- [ ] **Local Outlier Factor** — Density-based anomaly detection.
- [ ] **One-Class SVM** — Boundary-based anomaly detection.

📂 `07_Unsupervised_Learning/`

</details>

---

## 08. Model Evaluation

<details>
<summary><b>📁 Click to expand — Measuring how good your model really is</b></summary>

<br>

Metrics and techniques to validate, compare, and trust model performance.

- [ ] **Regression Metrics** — MAE, MSE, RMSE, R².
- [ ] **Classification Metrics** — Accuracy, Precision, Recall, F1-score.
- [ ] **Confusion Matrix** — Visualizing prediction outcomes.
- [ ] **ROC Curve** — True vs false positive rate trade-off.
- [ ] **Precision-Recall Curve** — Performance under class imbalance.
- [ ] **Cross Validation** — Robust performance estimation.
- [ ] **Bias-Variance Tradeoff** — Understanding underfitting vs overfitting.
- [ ] **Learning Curve** — Diagnosing model performance over data size.

📂 `08_Model_Evaluation/`

</details>

---

## 09. Hyperparameter Tuning

<details>
<summary><b>📁 Click to expand — Optimizing models for peak performance</b></summary>

<br>

Techniques to systematically search for the best model configuration.

- [ ] **GridSearchCV** — Exhaustive parameter search.
- [ ] **RandomizedSearchCV** — Randomized, faster parameter search.
- [ ] **Bayesian Optimization** — Probabilistic, informed search.
- [ ] **Optuna** — Efficient automated hyperparameter optimization.
- [ ] **Early Stopping** — Preventing overfitting during training.

📂 `09_Hyperparameter_Tuning/`

</details>

---

## 10. End-to-End Projects

<details>
<summary><b>📁 Click to expand — Real-world projects combining everything learned</b></summary>

<br>

Complete ML pipelines — from raw data to final predictions — applying concepts from all sections above.

- [ ] **House Price Prediction** — Regression on housing data.
- [ ] **Customer Churn Prediction** — Classification for retention analysis.
- [ ] **Heart Disease Prediction** — Medical diagnosis classification.
- [ ] **Loan Prediction** — Predicting loan approval outcomes.
- [ ] **Spam Detection** — Text classification for spam filtering.
- [ ] **Movie Recommendation** — Recommendation system basics.
- [ ] **Sales Prediction** — Time-aware regression forecasting.
- [ ] **Credit Card Fraud Detection** — Anomaly/classification on imbalanced data.

Each project includes: `notebook.ipynb`, `dataset.csv`, `output.png`, and `README.md`.

📂 `10_End_to_End_Projects/`

</details>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat-square)
![Scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-EB0028?style=flat-square)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 🚀 Getting Started

<details>
<summary><b>Click to expand setup instructions</b></summary>

<br>

**1. Clone the repository**
```bash
git clone https://github.com/your-username/Machine-Learning.git
cd Machine-Learning
```

**2. Create a virtual environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**5. Navigate to any topic folder and start learning!**

</details>

---

## 🤝 Contributing

<details>
<summary><b>Click to expand contribution guidelines</b></summary>

<br>

This is primarily a personal learning repository, but suggestions and corrections are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b improve-topic`)
3. Make your changes
4. Commit (`git commit -m "Improved explanation for XYZ"`)
5. Push (`git push origin improve-topic`)
6. Open a Pull Request

</details>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ If this repository helps your ML journey, consider giving it a star!

**Made with ☕ and curiosity — one notebook at a time.**

</div>
