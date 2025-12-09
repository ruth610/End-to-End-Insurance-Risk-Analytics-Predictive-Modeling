# End-to-End-Insurance-Risk-Analytics-Predictive-Modeling


Evaluate:

- R² / Adjusted R²
- RMSE / MAE
- Feature importance per ZIP

---

## **B. Premium Optimization Model**
Build a machine learning model to recommend **optimal premium values** using features from:

- Car characteristics
- Owner demographics
- Owner location
- Plan settings
- Engineered variables
- Any additional risk indicators

### **Recommended algorithms**
- Linear Regression / ElasticNet
- Random Forest

---

# 📈 **5. Model Evaluation and Interpretation**

Provide visual and numerical insights:

- Feature importance plots
- Actual vs predicted claims
- Geographic risk heatmaps
- Profitability segmentation
- Model accuracy metrics

Explain:

- Which features most influence risk
- Which customer groups are low-risk
- How premiums should be adjusted to attract low-risk clients

---

# 📘 **Final Report Requirements**


### **✔ Methodology**
- Data cleaning and preprocessing steps
- Hypothesis testing procedures
- Machine learning model selection
- Hyperparameter tuning
- Evaluation metrics

### **✔ Findings**
- Risk differences by province/zipcode
- Demographic risk differences
- Vehicle-related risk factors
- Premium and claims relationships
- Key predictors of TotalClaims
- ZIP codes and customer groups that are low-risk

### **✔ Recommendations**
- Pricing adjustments
- Marketing strategies for low-risk segments
- Plan features to adjust or enhance
- Customer segments to target for acquisition

---

# 📦 **Recommended Folder Structure**

ACIS-Risk-Analytics/
│
├── data/
│   ├── raw/                      # Original dataset (unchanged)
│   └── cleaned/                  # Cleaned & processed dataset
│
├── notebooks/
│   ├── 01_eda.ipynb                      # Exploratory Data Analysis
│   ├── 02_hypothesis_tests.ipynb         # Statistical tests & A/B testing
│   ├── 03_linear_models.ipynb            # Linear regression per zipcode
│   ├── 04_premium_prediction_model.ipynb # ML model for premium prediction
│
├── src/
│   ├── preprocessing.py          # Data cleaning pipeline
│   ├── feature_engineering.py    # Feature engineering scripts
│   ├── models.py                 # ML model definitions + training logic
│   ├── evaluation.py             # Metrics & evaluation utilities
│
├── reports/
│   └── final_report.pdf          # Final analytics & business report
│
└── README.md                     # Main project documentation


---

# 🧩 **Conclusion**
This project offers practical exposure to:

- Real insurance risk analysis
- Statistical modelling and hypothesis testing
- Predictive analytics for pricing
- Data engineering with complex datasets
- Delivering business-focused insights