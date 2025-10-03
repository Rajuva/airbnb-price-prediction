**Airbnb Price Prediction – Singapore**


**Project Overview**

This project predicts Airbnb listing prices in Singapore using machine learning models.  

The dataset was cleaned, explored, and used to train models like Linear Regression, Random Forest, and Gradient Boosting.  

The goal is to understand what factors influence Airbnb prices and estimate the price of new listings.  


**Dataset**  

\- Entries: ~1,000 listings (after cleaning: ~945)  

\- Target Variable: `price`  

\- Key Features Used:  
- `minimum\_nights`  
- `maximum\_nights`  
- `availability\_365`  
- Other numeric and categorical features  

**Data Cleaning Steps**

✔ Removed missing or invalid prices  

✔ Converted price strings (e.g., `$1,200`) into numeric format (`1200.0`)  

✔ Dropped/imputed missing values  

**Workflow**  

1\. Data Cleaning – handled missing values and cleaned features  

2\. EDA – checked data distributions and correlations  

3\. Feature Engineering – encoded categorical variables  

4\. Model Training – built 3 models:  
- Linear Regression  
- Random Forest  
- Gradient Boosting  

5\. Model Evaluation – compared performance  

**Model Results**


| Model              | MAE   | RMSE   | R² Score |

|--------------------|-------|--------|----------|

| Linear Regression  | ~53.88 | ~119.50 | ~0.567 |

| Random Forest      | ~44.61 | ~120.20 | ~0.562 |

| Gradient Boosting  | ~49.62 | ~117.85 | ~0.579 |



Gradient Boosting performed best overall.  

**Project Files**

airbnb-price-prediction/

│── cleaned\_airbnb\_data.csv # Cleaned dataset

│── Airbnb\_Price\_Prediction.ipynb # Jupyter Notebook

│── README.md # Documentation

**Future Improvements**
 Try XGBoost/LightGBM
 Add text analysis (amenities \& descriptions)
 Use location-based features (latitude \& longitude)
 Deploy as a web app (Flask/Streamlit)

**Author**
Rajuva 

