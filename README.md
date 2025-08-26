## Project Overview

The goal of this challenge is to classify subjects based on their cardiac magnetic resonance imaging (CMRI) scans into one of five diagnostic categories:

- **Healthy controls**
- **Myocardial infarction**
- **Dilated cardiomyopathy**
- **Hypertrophic cardiomyopathy**
- **Abnormal right ventricle**

These categories reflect a variety of structural and functional heart conditions that can be differentiated through careful analysis of cardiac morphology and function as captured in CMRI data.

## Approach

To tackle this classification task, we first extract a set of meaningful features from the medical images. These features are designed to reflect relevant physiological properties such as:

- Ventricular volumes  
- Myocardial thickness  
- Ejection fractions  

Once extracted, these features serve as input to various machine learning models, including:

- **Random Forests**
- **XGBoost**
- **Support Vector Machines**
- **Logistic Regression**

This pipeline emulates a clinically-inspired approach, where diagnostic decisions rely on interpretable and quantifiable markers derived from imaging, while leveraging the predictive power of modern machine learning classifiers.
