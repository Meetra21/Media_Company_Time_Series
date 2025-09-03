# Media Company Dataset – Viewership Analysis  

This project analyzes the **Media Company Dataset** to investigate why viewership declined for a newly launched show. The analysis applies **Linear Regression** and **Recursive Feature Elimination (RFE)** to identify the most significant factors affecting audience engagement.  

---

## 🎯 Project Goal  

- Understand **factors influencing viewership** trends for the show.  
- Use **linear regression** to model relationships between features and viewership.  
- Apply **Recursive Feature Elimination (RFE)** to select the most relevant predictors.  
- Provide insights into possible reasons for **declining viewership** and data-driven recommendations.  

---

## 📂 Dataset  

- **Source**: Media Company dataset.
- **Target Variable**: Viewership (number of viewers/engagement score).  
- **Features** (examples – actual features depend on dataset):  
  - Day/Week/Month (temporal trends)  
  - Marketing Spend (advertisements, promotions)  
  - Content Rating (user reviews, likes/dislikes)  
  - Platform Reach (regional penetration, device usage)  
  - Show-related features (genre, duration, etc.)  

---

## 🧭 Workflow  

### 1. Exploratory Data Analysis (EDA)  
- Analyze viewership trends over time.  
- Compare performance across different features (marketing spend, ratings, etc.).  
- Identify periods of decline in audience engagement.  

### 2. Modeling  
- **Linear Regression**: Build a baseline regression model to explain variance in viewership.  
- **Recursive Feature Elimination (RFE)**: Iteratively select the most important predictors for viewership.  

### 3. Evaluation  
- Assess model performance with R² and RMSE.  
- Compare baseline regression with feature-selected model.  
- Interpret coefficients to understand the influence of features.  

---

## 📂 Repository Structure  

- `data/` – Media company dataset (CSV format)  
- `notebooks/` – Jupyter notebooks for EDA and regression analysis  
- `models/` – Linear regression and RFE implementations  
- `results/` – Model summaries and feature selection reports  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/media-company-viewership-analysis.git
   cd media-company-viewership-analysis
