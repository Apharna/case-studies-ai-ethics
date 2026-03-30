# Predictive Customer Churn Analysis in Healthcare

## 🧠 Context
A global medical devices manufacturer serving healthcare providers through long-term contracts faced revenue leakage due to undetected changes in customer purchasing behavior.

## ⚠️ Problem
- Contract non-compliance due to reduced or irregular orders
- Late detection of churn signals
- Inefficient sales intervention
- Revenue loss and operational inefficiencies

## 🔍 Why It Matters
- Direct revenue impact from missed commitments
- Reduced customer lifetime value
- Poor allocation of sales efforts

## 🧪 Approach
- Built unsupervised customer segmentation using K-Means & hierarchical clustering
- Developed a churn risk scoring model using XGBoost
- Engineered features:
  - Purchase frequency
  - Contract utilization
  - Order value trends
- Designed a monthly batch classification pipeline

## 🛠️ Product Implementation
- Integrated predictions into account management dashboards
- Surfaced risk scores and next-best actions

## ⚖️ Trade-offs
- Batch processing vs real-time insights
- Model interpretability vs accuracy

## 🌍 Ethical Lens
- Bias in targeting segments
- Transparency in decision-making

## 💡 PM Takeaways
- Early signals matter more than reactive metrics
- Actionability > prediction accuracy

## 📊 Outcomes
- 15–22% reduction in revenue leakage
- 12–18% increase in retention

## 📦 Datasets
- Contracts
- Product data
- Transactions
