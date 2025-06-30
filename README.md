# Task5 Decision Tree and Random Forest Classifier Analysis                                                                                                                            

Heart Disease Prediction System                                                                                                                                         

This repository contains a complete implementation of decision tree and random forest classifiers for predicting heart disease risk using the Heart Disease dataset. This demonstrates machine learning workflows including data preprocessing, model training, evaluation, visualization, and interpretation.                                                    

**Key Features:**

1. End-to-end ML pipeline from data loading to model evaluation
2. decision tree visualization
3. Overfitting analysis with depth tuning
4. Comparative performance evaluation (accuracy + cross-validation)
5. Feature importance interpretation for both models
6. Comprehensive visual analytics (4 diagnostic plots)                                                                                                                  

                      
**Dataset:**                                                                                                                                                         

The UCI Heart Disease Dataset contains 303 patient samples with 13 clinical features collected from four medical institutions.

1. age - Patient age in years
2. sex - Gender (0 = female, 1 = male)
3. cp - Chest pain type (0-3 scale: asymptomatic/typical/atypical/non-anginal)
4. trestbps - Resting blood pressure (mm Hg)
5. chol - Serum cholesterol (mg/dl)
6. fbs - Fasting blood sugar > 120 mg/dl (0/1)
7. restecg - Resting electrocardiographic results
8. thalach - Maximum heart rate achieved
9. exang - Exercise induced angina (0/1)
10. oldpeak - ST depression induced by exercise
11. slope - Slope of peak exercise ST segment
12. ca - Number of major vessels colored by fluoroscopy (0-3)
13. thal - Thalassemia type (1-3: normal/fixed defect/reversible defect)                                                                                                    

**Class Distribution:**

Healthy: 138 samples (45.5%)                                                                                                                                         
Heart Disease: 165 samples (54.5%)                                                                                                                                   

**Installation**

Clone repository:                                                                                                                                                     
git clone https://github.com/Sriyoshija/heart-disease-prediction.git                                                                                                     
cd heart-disease-prediction                                                                                                                                            

Create virtual environment:                                                                                                                                          
python -m venv venv                                                                                                                                                  
source venv/bin/activate  # Linux/macOS                                                                                                                                       
venv\Scripts\activate    # Windows                                                                                                                                   

Install dependencies:                                                                                                                                                        
pip install pandas numpy matplotlib scikit-learn graphviz                                                                                                              

**Workflow:**                                                                                                                                                        
*I took reference from this workflow and implemented*                                                                                                                 

![image](https://github.com/user-attachments/assets/70e50aba-550c-4325-9207-5279667d1475)
                                                                                                                                                                                                      
                                                                                                                                                              
**References:**                                                                                                                                                      

   Scikit-learn Documentation:                                                                                                                                       
Decision Trees: https://scikit-learn.org/stable/modules/tree.html                                                                                                         
Random Forests: https://scikit-learn.org/stable/modules/ensemble.html#forest                                                                                           
Graphviz Visualization: https://graphviz.org/doc/info/lang.html                                                                                                       
Cardiovascular Risk Prediction: https://www.ahajournals.org/doi/10.1161/CIR.0000000000000638



