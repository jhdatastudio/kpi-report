# Demo 07 – Churn Strategy Dashboard

This project showcases a full churn analytics pipeline, including predictive modeling in R and executive-facing reporting in Looker Studio. It is designed for freelance portfolios, product strategy teams, or data consultants delivering B2C churn insights.

## 🔍 Objective

To identify high-risk customer segments and actionable retention levers through:
- Binary churn prediction
- Driver analysis
- Strategic dashboarding
- Segment-specific business recommendations

---

## 🧠 Key Features

### Predictive Modeling (R)
- Logistic regression (`glm`) with stepwise selection
- ROC/AUC score: 0.935
- Churn risk scoring with threshold calibration
- Confusion matrix and true positive identification

### Visual Insights (Looker Studio)
- Churn by Age Group, Complains, and Tenure
- Conditional heatmap by Subscription Length × Age Group
- Predicted churn vs. charge scatterplot
- Filters for Status, Complains, Age Group
- Risk-segment table with action tagging

---

## 📊 Dashboard Preview

Built in **Looker Studio**, but reproducible in Tableau or Power BI.

▶️ **[View Live Dashboard](https://lookerstudio.google.com/reporting/55b42e94-8a03-4d65-bcab-9aca677ad339)**

Includes:
- Executive KPIs
- Churn driver visuals
- Actionable segment flags
- Outreach tracking & revenue views

---


## 🧩 Tech Stack

- R + tidyverse + caret + pROC
- Looker Studio (Google Sheets connector)
- Optional: Power BI, Tableau (fully portable)

---

## 💡 About the Author

This demo was created by **JH Data Studio** — delivering tailored analytics, AI strategy, and automation for smarter decisions.

> 👉 Visit [jhdatastudio.com](https://jhdatastudio.com) to learn more or book a discovery call.
