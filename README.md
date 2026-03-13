# Customer Behavioral Segmentation

**Author:** Risalat Masrafi  
**Admin No:** P2508290  
**Class:** DAAA/FT/1B/04

---

## Project Overview
This project implements a comprehensive unsupervised machine learning pipeline to segment a customer base into distinct behavioral personas. Using the **Scikit-Learn** library, the analysis transitions from raw demographic observations to a sophisticated multi-dimensional clustering model. 

The goal is to identify non-obvious patterns in customer behavior, providing a mathematical foundation for understanding how **Age** and **Annual Income** drive **Spending Engagement**.

## Dataset Description
The analysis uses the `CA2-Customer-Data.csv` file, containing 200 customer observations with the following features:
* **Age:** Demographic variable identifying generational shifts.
* **Annual Income (k$):** Measure of financial capacity and purchasing power.
* **Spending Score (1–100):** Behavioral metric based on historical engagement.

## Machine Learning Workflow
1. **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations.
2. **Data Preprocessing:** Feature scaling using `StandardScaler` to normalize the 3D feature set.
3. **K-Means Clustering:** * Optimal clusters determined via the **Elbow Method (WCSS)**.
    * Validation performed using **Silhouette Analysis** (Score: 0.428).
4. **Dimensionality Reduction:**
    * **PCA (Principal Component Analysis):** Reducing data to 2D for global variance visualization.
    * **t-SNE:** Non-linear reduction to confirm cluster local density and robustness.
5. **Cluster Profiling:** Defined 6 statistically unique personas based on the intersection of age, wealth, and spending habits.

## Getting Started

### Prerequisites
Ensure you have Python installed. It is recommended to use a virtual environment.

### Installation
1. **Clone the repository:**
   ```bash
   git clone # ST1511 CA2 – Part A: Customer Behavioral Segmentation

**Author:** Risalat Masrafi  
**Admin No:** P2508290  
**Class:** DAAA/FT/1B/04

---

## Project Overview
This project implements a comprehensive unsupervised machine learning pipeline to segment a customer base into distinct behavioral personas. Using the **Scikit-Learn** library, the analysis transitions from raw demographic observations to a sophisticated multi-dimensional clustering model. 

The goal is to identify non-obvious patterns in customer behavior, providing a mathematical foundation for understanding how **Age** and **Annual Income** drive **Spending Engagement**.

## Dataset Description
The analysis uses the `CA2-Customer-Data.csv` file, containing 200 customer observations with the following features:
* **Age:** Demographic variable identifying generational shifts.
* **Annual Income (k$):** Measure of financial capacity and purchasing power.
* **Spending Score (1–100):** Behavioral metric based on historical engagement.

## Machine Learning Workflow
1. **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations.
2. **Data Preprocessing:** Feature scaling using `StandardScaler` to normalize the 3D feature set.
3. **K-Means Clustering:** * Optimal clusters determined via the **Elbow Method (WCSS)**.
    * Validation performed using **Silhouette Analysis** (Score: 0.428).
4. **Dimensionality Reduction:**
    * **PCA (Principal Component Analysis):** Reducing data to 2D for global variance visualization.
    * **t-SNE:** Non-linear reduction to confirm cluster local density and robustness.
5. **Cluster Profiling:** Defined 6 statistically unique personas based on the intersection of age, wealth, and spending habits.