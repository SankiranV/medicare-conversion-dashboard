# Medicare Conversion Prediction Dashboard

An end-to-end machine learning project to predict insurance policy conversions using SHAP explainability and Tableau visual dashboards.

## Problem

Health insurance companies struggle to identify which customers are likely to purchase policies. This project uses predictive analytics to support conversion strategies.

## Approach

- Cleaned and prepared real-world structured health insurance data
- Built baseline models with Random Forest & XGBoost
- Tuned hyperparameters and handled class imbalance with `scale_pos_weight`
- Explained predictions using SHAP values
- Visualized results and key insights with Tableau dashboards

## Results

- **Best Model**: XGBoost (AUC: 0.86)
- **Top Predictors**: Vehicle Age, Vintage, Previously Insured
- **Conversion Insights**: Males aged 30–40 had higher likelihood to convert

## Structure
├── 01_EDA.ipynb
├── 02_Preprocessing.ipynb
├── 03_Modeling.ipynb
├── 04_Advanced_Models.ipynb
├── 05_Explainability.ipynb
├── 06_Dashboard_DataPrep.ipynb
├── dashboards/
│   └── predictions_with_shap.csv
├── images/
│   └── [screenshots of Tableau dashboard]
└── README.md

## Dashboards

Interactive Tableau Public link: [Click here](https://public.tableau.com/views/MedicareConversionPredictionDashboard/MedicareConversionDashboardPredictionInsightswithSHAPSegments?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Tech Stack

Python, scikit-learn, XGBoost, SHAP, Pandas, Tableau Public

## Author

[Sankiran Vala](https://github.com/SankiranV)
