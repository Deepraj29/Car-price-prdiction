🚗 Car Price Prediction

This project predicts the selling price of used cars using the Cardekho dataset. It applies machine learning techniques with feature engineering, preprocessing, and model training to provide accurate predictions.

📂 Dataset

The dataset (cardekho.csv) contains information about used cars with features such as:

year – Year of manufacture

selling_price – Target variable (car’s selling price)

km_driven – Kilometers driven

fuel – Fuel type (Petrol, Diesel, CNG, etc.)

seller_type – Individual/Dealer

transmission – Manual/Automatic

owner – Ownership type

mileage, engine, max_power, seats

brand – Extracted from car name

⚙️ Project Workflow

Data Preprocessing

Handled missing values

Extracted brand name from car model

Converted categorical variables using Label Encoding

Cleaned numeric fields like max_power

Standardized features

Model Training

Linear Regression

Random Forest Regressor (with hyperparameter tuning using GridSearchCV)

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score (explained variance, treated as “accuracy”)

Visualizations

Correlation Heatmap

Distribution of Selling Price

Fuel Type vs Average Price

Transmission vs Selling Price

Seats vs Selling Price

Actual vs Predicted (Random Forest)

Feature Importance from Random Forest

📊 Results

Linear Regression: ~60–70% R² Score

Random Forest (Tuned): ~75–85% R² Score

Random Forest performed significantly better after feature engineering and hyperparameter tuning.
