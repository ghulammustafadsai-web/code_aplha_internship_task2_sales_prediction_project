# Sales Prediction using Machine Learning
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![CodeAlpha](https://img.shields.io/badge/Internship-CodeAlpha-blue?style=for-the-badge)

## 📌 Project Overview
Developed during my **CodeAlpha Internship**, this project focuses on predicting product sales based on advertising expenditures across various media channels. By leveraging machine learning, the model helps businesses optimize their marketing budget to maximize revenue.

## 📊 Dataset
The dataset contains advertising spends for:
- **TV**: Dollars spent on TV ads.
- **Radio**: Dollars spent on Radio ads.
- **Newspaper**: Dollars spent on Newspaper ads.
- **Sales**: Total units sold (Target Variable).

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **ML Models**: Linear Regression, Random Forest Regressor

## 🚀 Key Results
The **Random Forest Regressor** outperformed other models with exceptional accuracy:
- **R² Score**: ~0.98 (98% accuracy in variance explanation)
- **Primary Driver**: TV advertising (contributes >60% to sales prediction)

## 💡 Strategic Insights
1. **Prioritize TV**: TV ads are the strongest predictor of sales.
2. **Synergy**: Radio acts as a powerful secondary channel to boost campaigns.
3. **Budget Optimization**: Newspaper ads showed minimal correlation with sales; budget reallocation is advised.
4. **Predictability**: High model confidence allows for data-driven forecasting of future sales cycles.

## 📂 Project Structure
```text
├── code_alpha_sales_prediction_task.ipynb  # Full analysis & Model building
├── Advertising.csv                         # Dataset
└── README.md                               # Project Documentation
