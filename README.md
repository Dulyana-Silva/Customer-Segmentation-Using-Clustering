# Customer Segmentation Using Clustering Techniques 🛍️

This project focuses on applying **unsupervised machine learning** (clustering) to segment customers of a retail mall based on demographic and behavioral data. The goal is to uncover patterns that help businesses **personalize marketing strategies** and improve customer experience.

---

## 📌 Business Problem

Retailers often serve a diverse customer base. Without segmentation, marketing campaigns can be inefficient and poorly targeted. This project solves this problem by using **clustering** to group customers with similar behaviors, enabling the business to:

- Identify high-value vs. low-engagement customers
- Personalize promotions and loyalty programs
- Improve marketing ROI

---

## 🎯 Objectives

- Apply clustering techniques (KMeans) on customer data  
- Use EDA to understand relationships and feature importance  
- Test sampling techniques (random & stratified)  
- Standardize features to ensure fair clustering  
- Visualize and interpret resulting customer segments

---

## 🧾 Dataset

- **Source**: Seaborn built-in dataset  
- **Name**: `mall_customers.csv`  
- **Records**: 200 customers  
- **Features**:
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🛠️ Technologies Used

- Python
- pandas
- seaborn & matplotlib
- scikit-learn (KMeans, preprocessing, train_test_split)

---

## 📊 Project Workflow

1. **Data Loading and Cleaning**
2. **Exploratory Data Analysis (EDA)**
   - Feature distributions
   - Pairplots & correlation matrix
3. **Sampling**
   - Random sampling (30%)
   - Stratified sampling based on Gender
4. **Feature Standardization**
   - Using `StandardScaler`
5. **Clustering**
   - KMeans clustering
   - Elbow method for optimal K
6. **Cluster Visualization**
   - Income vs. Spending Score
7. **Cluster Analysis & Business Insights**

---

## 📈 Visuals

<p align="center">
  <img src="images/elbow-method.png" alt="Elbow Method" width="500"/>
</p>

<p align="center">
  <img src="images/customer-segments.png" alt="Customer Segments" width="500"/>
</p>

> *(Include plots as PNGs in an `images/` folder in your repo)*

---

## 🧠 Key Insights

| Cluster | Description                          | Suggested Strategy               |
|---------|--------------------------------------|----------------------------------|
| 0       | Low income, high spenders            | Introduce loyalty programs       |
| 1       | Average income and moderate spenders | Upsell with bundled offers       |
| 2       | High income, high spenders           | Target with premium deals        |
| 3       | High income, low spenders            | Re-engage with exclusive rewards |

---

## 📌 Future Improvements

- Try advanced clustering methods (DBSCAN, Hierarchical)
- Add more features (e.g., online behavior, frequency of visits)
- Deploy as an interactive dashboard using Streamlit or Dash

---

### 📍Project Objective: Segment customers to support marketing strategy.
### 📊EDA Findings: Income and spending score show clear groupings.
### ⚙️Model: Used KMeans clustering after standardization.
### 🧠Insights:
- Cluster 0: Low income, high spenders → Target with budget offers
- Cluster 2: High income, high spenders → Luxury promotions
### 📌Conclusion: Clustering helps build data-driven customer targeting.
