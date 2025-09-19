# Experimental and Theoretical Investigation of MOF Adsorbents for Post-Combustion Carbon Capture

This repository contains machine learning models developed to predict the gas selectivity of metal-organic frameworks (MOFs), with a focus on **CO₂/N₂ selectivity** for post-combustion carbon capture.  
The work combines structural, physical, and chemical descriptors of MOFs with supervised learning methods.

---

## Dataset
The dataset includes physical and chemical descriptors:  
- Density  
- Gravimetric & Volumetric Surface Area  
- Void Fraction, Pore Volume  
- Largest Cavity Diameter, Pore Limiting Diameter  
- Additional chemical descriptors (e.g., electronegativity ratios, metal percentage, degree of unsaturation)  

### Target Variables
- **Kh CO₂ / Kh N₂**  
- **Kh CH₄ / Kh N₂**  
- **Kh O₂ / Kh N₂**

---

## Models Implemented
- Linear Regression  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- XGBoost Regressor  
- CatBoost Regressor  
- Gradient Boosting, AdaBoost, Extra Trees  
- Artificial Neural Networks (ANN)  

---

## Results
- **CH₄/N₂** and **O₂/N₂** selectivity predictions achieved good accuracy (R² > 0.6 for ensemble and ANN models).  
- **CO₂/N₂** selectivity was more challenging due to complex interactions, with limited R² improvement.  
- Feature engineering and multicollinearity analysis provided insights into **structure–property relationships** for MOFs.  

---

## Tools & Libraries
- **Python 3.x**  
- Scikit-learn  
- XGBoost  
- CatBoost  
- TensorFlow / Keras (for ANN)  
- Pandas, NumPy, Matplotlib, Seaborn  
