# 🛡️ Insurance Loss Analytics
**How Can We Predict Insurance Risk and Set Fair Premiums?**  
*Predicting Loss Costs and Claims Using Machine Learning*  
**Tools**: Python | Pandas | NumPy | Scikit-learn | XGBoost | LightGBM | Matplotlib

---

## 🔍 Methodology
<details>
<summary>Click to expand</summary>

### Loss Cost (LC) and HALC Prediction
- Modeled LC (Loss Cost) and HALC (Historically Adjusted Loss Cost) using Tweedie GLM, LightGBM, XGBoost, and Neural Networks.
- Evaluation metric: **Root Mean Squared Error (RMSE)**.

### Claim Status (CS) Classification
- Predicted claim occurrence (CS: 1 = claim made, 0 = no claim) using Logistic Regression, Random Forest, and XGBoost classifiers.
- Evaluation metric: **ROC-AUC Score**.

### Feature Engineering
- Created features such as policyholder age, policy duration, vehicle age, and driver experience.
- Encoded categorical variables and transformed datetime variables for modeling.

### Handling Data Challenges
- Addressed highly skewed, zero-inflated data patterns.
- Imputed missing values in `X.27` (Fuel Type) using XGBoost classification.

</details>

---

## 📌 Project Highlights
<details>
<summary>Click to expand</summary>

- **Prediction Accuracy**: Achieved strong RMSE for regression and high ROC-AUC for classification.
- **Balanced Modeling**: Managed the trade-off between model complexity and interpretability.
- **Business Perspective**: Focused on prediction accuracy to support fair pricing and avoid adverse selection.
- **Variable Selection**: Emphasized driver characteristics, vehicle attributes, policy details, and location factors.

</details>

---

## 📁 Deliverables
- 📄 *Insurance Loss Analytics Report.pdf*
- 📄 *Insurance Modeling Code Workbook.ipynb*

---

## 📈 Key Takeaway
⭐ **Accurate prediction of loss costs and claim risks is critical for setting fair premiums, improving profitability, and minimizing underwriting risk — even if it sacrifices full model transparency.**
