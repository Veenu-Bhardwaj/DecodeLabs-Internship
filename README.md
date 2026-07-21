# DecodeLabs-Internship

## Completed Projects

### Week 1: Advanced EDA & Feature Engineering
- Missing data handled via 5/20% threshold rule
- Outliers capped via IQR method on Fare and Age
- 3 new engineered features: FamilySize, IsAlone, FarePerPerson
- Final dataset: 889 rows × 12 columns
- [Week1_Data_Science/DecodeLabs_Project1_EDA.ipynb](Week1_Data_Science/DecodeLabs_Project1_EDA.ipynb)

### Week 2: Fraud Detection Pipeline (Supervised Learning)
- Leak-free pipeline using imblearn.pipeline.Pipeline (SMOTE + StandardScaler applied only within CV folds)
- Logistic Regression: Test ROC-AUC 0.9715
- Random Forest: Test ROC-AUC 0.9853 (best precision-recall tradeoff for production use)
- [Week2_Data_Science/DecodeLabs_Project2_FraudDetection.ipynb](Week2_Data_Science/DecodeLabs_Project2_FraudDetection.ipynb)

### Week 3: Customer Segmentation (Unsupervised Learning)
- PCA (3 components) + K-Means (K=4, validated via Elbow Method + Silhouette Score)
- Dataset: Customer Personality Analysis (2,236 customers)
- 4 business personas identified: Budget-Conscious Browsers, Affluent Loyalists, Premium VIPs, Mature Value Seekers
- [Week3_Data_Science/DecodeLabs_Project3_CustomerSegmentation.ipynb](Week3_Data_Science/DecodeLabs_Project3_CustomerSegmentation.ipynb)

## Tech Stack
Python, Pandas, Scikit-learn, Imbalanced-learn, Matplotlib, Google Colab
