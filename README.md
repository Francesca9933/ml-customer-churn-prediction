# ml-customer-churn-prediction
With the rapid development of the telecommunication industry, the service providers are more inclined towards the expansion of the subscriber base. To survive in the competitive environment, the retention of existing customers has become a huge challenge. It is stated that the cost of acquiring a new customer is far more than for retaining the existing one. Therefore, it is essential for the telecom industries to use advanced analytics to understand consumer behavior an, in turn, predict the association of the customers as whether or not they will leave the company.</br>
</br>

This Machine Learning project is dedicated to building a forecasting model of a Telecom's customer churn. Based on customer level information, the project focuses on analyzing the dependencies of several data points with one another, taking into account trends and seasonal changes, as well as studying and applying various machine learning algorithms. </br>
</br>

**Main Tasks**
- Understand business data to find successful ways to analyze it and remove possible drivers of distortion
- Find the best model among the known ones to faithfully predict churn probability
- Use the statistical and ML insights to propose marketing strategies to increase retention rate

## 📁 Repository Structure
```text
ml-customer-churn-prediction/
├── customer_churn_prediction.ipynb            # Python notebook of scripts
├── assets/                                    # Forecast plots and evaluation charts
├── report/                                    # PDF Latex File report and PDF presentation
│ ├── Customer_Churn_Presentation
│ └── Customer_Churn_Forecasting_Report
├── .gitattributes
├── .gitignore
├── .python-version
├── requirements.txt
├── LICENSE
└── README.md
```

## 🗎 Project Structure
```text
customer_churn_prediction.ipynb/
├── Import libraries
├── Data Import
├── Attributes Description
├── Data Profiling
│ ├── Visualize Class Imbalance
  ├── Identify Correlations
│ └── The Heavy User Paradox
├── Data Preprocessing
│ ├── Data cleaning
│ ├── Statistics for DataUsage
│ ├── Statistics for DayMins
│ ├── Outlier Detection
│ ├── Isolation Forest for Outlier Detection
│ └── Logarithmic Transformation
├── Modeling  
│ ├── Standardization
│ ├── Check Prediction Complexity
│   ├── PCA
│   ├── t-SNE
  ├── AutoML with FLAML 
  ├── Try out Models for Demonstration
    ├── Logistic Regression
    ├── Decision Tree
    ├── Random Forest 
    ├── XGBoost
    ├── ANN Experimentation
    ├── K-Means
      └── SHAP
```

## Results 
It is useful to divide the dataset into 4 groups of customers with similar characteristics (unsupervised classification using K-Means). Based on their common traits, we could assign a label to each group that grasps the main behavior: 
- Persona 0: Chronic Churner
- Persona 1: Quiet Loyalist
- Persona 2: Premium Data User
- Persona 3: Price-Sensitive Light User
Our target to decrease churning rate tends to Persona 0 and 3, providing business and marketing solutions such as add-ons, Overage Forgiveness, on-boarding techniques, contract incentives and entry-level bundles. 
