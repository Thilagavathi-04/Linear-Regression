# Housing Price Prediction Using Linear Regression

## Project Overview

This project applies **Simple and Multiple Linear Regression** techniques to predict housing prices based on various features such as area, bedrooms, bathrooms, amenities, and furnishing status.

The dataset consists of 13 key features that influence house pricing, including both numerical and categorical data.

---

## Dataset Description

The dataset (`housing.csv`) contains the following key features:

- **Price:** Target variable (house price)
- **Area:** Total area in square feet
- **Bedrooms:** Number of bedrooms
- **Bathrooms:** Number of bathrooms
- **Stories:** Number of stories in the house
- **Mainroad:** Whether the house is connected to the main road (Yes/No)
- **Guestroom:** Availability of guest room (Yes/No)
- **Basement:** Presence of basement (Yes/No)
- **Hotwaterheating:** Presence of hot water heating (Yes/No)
- **Airconditioning:** Presence of air conditioning (Yes/No)
- **Parking:** Number of parking spaces
- **Prefarea:** Location in a preferred area (Yes/No)
- **Furnishingstatus:** Furnishing condition (Fully Furnished, Semi-Furnished, Unfurnished)

---

## Project Workflow

1. **Data Import & Preprocessing**
   - Load dataset
   - Encode categorical features (binary encoding and one-hot encoding)
   - Handle missing values

2. **Train-Test Split**
   - Split dataset into training (80%) and testing (20%) sets

3. **Model Training**
   - Train Linear Regression model using `scikit-learn`

4. **Model Evaluation**
   - Evaluate using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score

5. **Visualization & Interpretation**
   - Plot regression results for the key feature (Area)
   - Analyze regression coefficients to understand feature impact

---

## Conclusion

- The linear regression models demonstrated that **house area** is a significant predictor of price.
- Incorporating multiple features substantially improved prediction accuracy, as reflected in higher R² and lower error metrics.
- Encoding categorical variables and performing multicollinearity checks ensured a robust and reliable model.
- Visualizations aided in interpreting the model and identifying relationships between features and price.
- This foundational work paves the way for applying more advanced machine learning models for real estate price prediction.

---
