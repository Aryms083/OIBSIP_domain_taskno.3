# OIBSIP_domain_taskno.3
📌 Objective
Predict used car prices using historical vehicle data. The goal is to build a regression model that estimates a car's market value based on its attributes like age, mileage, brand, and fuel type .

🔍 Steps Performed
Data Loading & Overview

Loaded a used‑car dataset including features such as year, mileage, fuel_type, transmission, seller_type, owner, and the target variable selling_price.

Inspected dataset structure and identified data types.

Exploratory Data Analysis (EDA)

Explored distributions of numeric features (e.g., mileage, year).

Analyzed relationships with car price using scatterplots and box plots.

Calculated correlation matrix for numeric variables.

Evaluated impact of categorical features (e.g., fuel type, transmission) on price.

Data Cleaning & Preprocessing

Checked and handled missing values or duplicates.

Converted categorical variables to numeric via encoding (e.g., One-Hot Encoding for variables like fuel_type, transmission).

Scaled or normalized numeric features if needed to improve model performance.

Train–Test Split

Split data into training and testing sets (commonly 75% train, 25% test).

Model Building & Evaluation

Trained regression models (typically Linear Regression, and possibly Random Forest Regressor or Gradient Boosting).

Evaluated performance using metrics such as Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R² score.

Conducted residual analysis and compared actual vs predicted prices visually.

Model Interpretation

Examined feature importance or regression coefficients to determine which car attributes significantly influence price.

🛠️ Tools & Libraries Used
Python: pandas, NumPy for data handling and manipulation

Visualization: matplotlib, seaborn for plots

ML Tools: scikit-learn for train–test splitting, encoding, model training, and evaluation

✅ Outcome
Produced a regression model capable of reasonably predicting used car prices from key attributes.

Gained insights into which factors (e.g., manufacturing year, mileage, fuel type) have the most influence on market value.

Demonstrated end-to-end data science workflow: data import → cleaning → EDA → modeling → evaluation.

🧭 How to Use
Download the car-price dataset (likely a CSV with specified features).

Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Execute the notebook sections in order:

Data loading → EDA → Preprocessing → Modeling → Evaluation

Optionally input new car attributes to predict selling price using the trained model.

🚀 Conclusion
This notebook offers a practical demonstration of regression modeling applied to real-world used-car price prediction. It methodically walks through data exploration, feature engineering, model training, and interpretation—making it a valuable learning resource for beginners in data science and predictive modeling
