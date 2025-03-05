# Crash Craft - Machine Learning 🏎️

**Crash Craft** is a machine learning-driven analysis of accident patterns in the United States. The project leverages various machine learning models to predict accident severity, identify high-risk scenarios, and extract meaningful insights from accident data.

**[Project Website](https://sites.google.com/view/trinaymlproject/home?authuser=0)**

---

## Introduction
Accidents are a significant concern in modern transportation, and understanding their causes is crucial for reducing fatalities and injuries. This project analyzes U.S. accident data to:
- Identify key factors contributing to accidents.
- Predict accident severity using machine learning models.
- Cluster accident data to uncover hidden patterns.

The dataset includes information on weather conditions, road types, accident severity, and timestamps, among other features.

---

## Project Structure

Crash-Craft---Machine-Learning/
│
├── Code notebooks/ # Jupyter Notebooks for different ML models
│ ├── Data Cleaning
│ ├── Data Extraction
│
├── Data/ # Dataset files
│
├── Models/ # Code for all Models
│
├── Presentation/ #PPT and Recording
│
├── Website/ #link for website is present here
│
├── README.md # This README file
│
└── requirements.txt # Required dependencies

---

## 🧠 Machine Learning Models

### 1️ **Decision Tree Classifier**
- Achieved **73.3% accuracy**.
- Provided interpretable rules and feature importance insights.

### 2️ **Random Forest Classifier**
- Outperformed Decision Tree with **78% accuracy**.
- Balanced between precision and recall for severe accidents.

### 3️ **Naive Bayes Classifier**
- Probabilistic approach useful for classification.
- Struggled with unbalanced severity data but was adjusted through sampling.

### 4️ **Support Vector Machine (SVM)**
- Used **linear and polynomial kernels**.
- Achieved **59-60% accuracy**.
- Polynomial kernel improved recall for severe accidents.

### 5️ **Neural Networks (ANN)**
- Trained using a **Sequential model with Dense layers**.
- Accuracy was around **51%**, indicating the need for hyperparameter tuning.

### 6️ **Clustering (K-Means)**
- Applied **3-cluster and optimal-cluster K-Means** for accident segmentation.
- Showed distinct groups based on accident characteristics.

### 7️ **Association Rule Mining (Apriori)**
- Found strong correlations between accident attributes (e.g., weather, road conditions).
- Generated rules with high **confidence and lift** for accident risk factors.


---

## Performance Summary

| Model | Accuracy | Precision | Recall | Key Observations |
|--------|---------|----------|--------|------------------|
| **Decision Tree** | 73.3% | 0.78 | 0.78 | Simple model with clear interpretability. |
| **Random Forest** | 78% | 0.79 | 0.78 | Best traditional ML model, avoids overfitting. |
| **Naive Bayes** | ~70% | Moderate | Moderate | Sensitive to class imbalance. |
| **SVM (Linear Kernel)** | 59% | 0.60 | 0.59 | Limited performance due to data complexity. |
| **SVM (Polynomial Kernel)** | 56% | 0.59 | 0.57 | Better recall but lower precision. |
| **Neural Network** | 51% | - | - | Underperformed due to architecture limitations. |
| **Clustering (K-Means)** | N/A | N/A | N/A | Segmented accidents into meaningful groups. |
| **Association Rule Mining** | N/A | N/A | N/A | Identified strong relationships among accident attributes. |

🔹 **Key Findings**:
- **Random Forest was the best predictor**, balancing accuracy and recall.
- **Neural Networks underperformed**, requiring further optimization.
- **SVMs struggled with performance**, especially with complex non-linear relationships.
- **Clustering revealed hidden patterns**, and **Association Rule Mining** provided risk insights.

🔹 **Key Findings**:
- **Random Forest outperformed the Decision Tree** with higher accuracy and better generalization.
- **Feature Importance Analysis**: Road conditions, time of day, and weather conditions were key predictors of accident severity.
- **Clustering Analysis**: Accidents grouped into distinct types (e.g., nighttime highway crashes, urban rush-hour incidents).

---

## Results and Insights

 **Key Patterns Identified**:
1. **Time-Based Trends**: Peak accident times correlate with rush hours.
2. **Weather Influence**: Fog and rain significantly impact accident severity.
3. **Road Type Impact**: Highways see more severe accidents compared to urban streets.

**For a detailed breakdown of results, visit the [project website](https://sites.google.com/view/trinaymlproject/home?authuser=0).**

---
