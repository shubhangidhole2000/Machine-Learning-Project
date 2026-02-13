# Machine-Learning-Project
Machine learning is used to analyze patient medical data and predict heart disease using algorithms like K-Nearest Neighbors, Decision Tree, and Random Forest. This helps identify high-risk patients and understand key risk factors for better healthcare decision-making.

# Heart Disease Prediction Using Machine Learning

## Overview
This project predicts whether a person has heart disease using medical data and machine learning algorithms. It provides insights into patient risk factors and allows analysis of feature importance and model performance.

## Tools Used
- Python  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`  
- CSV Dataset (Patient Data)  

## Project Workflow
1. **Data Collection:** Imported heart disease dataset from CSV.  
2. **Data Exploration:** Checked dataset shape, columns, data types, null values, and summary statistics.  
3. **Data Visualization:** Plotted histograms and countplots to understand data distribution and balance.  
4. **Feature Engineering:**  
   - Correlation heatmap to identify important features.  
   - Converted categorical features into numerical using one-hot encoding.  
5. **Feature Scaling:** Scaled numerical columns (`age`, `resting_blood_pressure`, `cholesterol`, `max_heart_rate`, `st_depression`) using StandardScaler.  
6. **Model Building:** Tested three ML algorithms:  
   - **K-Nearest Neighbors (KNN)**  
   - **Decision Tree Classifier**  
   - **Random Forest Classifier**  
7. **Model Evaluation:** Used cross-validation to find best parameters (K for KNN, max_depth for Decision Tree, n_estimators for Random Forest) and compared accuracy.

## Key Insights
- **Best Model:** KNN achieved the highest accuracy of **84.48%**.  
- **Important Risk Factors:** Age, chest pain type, cholesterol, resting blood pressure, ST depression, and maximum heart rate.  
- **Dataset Balance:** Target variable (presence/absence of heart disease) is nearly balanced.  
- **Feature Correlations:** Heatmap shows strong relationships among key medical indicators.
- 
## Conclusion
This project demonstrates how machine learning models can accurately predict heart disease and highlight the most important risk factors, enabling better preventive healthcare measures.

## Author
**Shubhangi Dhole**  
Aspiring Data Analyst | Learning Machine Learning  

---

