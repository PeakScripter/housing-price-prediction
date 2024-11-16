# Paris Housing Price Prediction

This project uses a dataset of housing prices in Paris to develop a predictive model for determining housing prices based on various features. The workflow involves data exploration, preprocessing, training a regression model, and evaluating its performance.

## Project Features
- **Dataset**: The dataset contains features like square meters, number of rooms, yard availability, pool presence, floors, and housing prices.
- **Regression Model**: A Linear Regression model is implemented using `scikit-learn`.
- **Metrics**: Evaluation metrics include Mean Squared Error (MSE) and R-squared (R²).
- **Libraries**: Key libraries include `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

---

## Project Structure

1. **Data Loading**:  
   The dataset is loaded and explored to understand its structure and statistics.

2. **Data Preprocessing**:  
   - Separate features (X) and the target variable (`price`).
   - Split data into training and testing sets.

3. **Model Training**:  
   A `LinearRegression` model is trained on the preprocessed data.

4. **Model Evaluation**:  
   - Predictions are generated on the test data.
   - Evaluation metrics (MSE, R²) are calculated to measure performance.

5. **Visualization**:  
   - Use `matplotlib` and `seaborn` to visualize relationships between features and the target variable.

---

## How to Run the Project

1. **Dependencies**:  
   Ensure you have the following Python libraries installed:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```

2. **Dataset**:  
   Place the dataset (`ParisHousing.csv`) in the same directory as the notebook or script.

3. **Execution**:  
   Run the cells in the Jupyter Notebook sequentially to train and evaluate the model.

---

## Results
This project demonstrates the basics of predictive modeling and evaluation in housing price prediction.
![Screenshot 2023-12-23 080155](https://github.com/legend-of-tomorrow/housing-price-prediction/assets/122628663/4e2130dd-68bb-4520-9c04-8a11d80cbcaa)

![Screenshot 2023-12-23 080133](https://github.com/legend-of-tomorrow/housing-price-prediction/assets/122628663/2fc5c2ab-95d7-4930-a7e7-9cd6537d04f5)
- **Model Performance**:
  - **Mean Squared Error (MSE)**: ~3,544,654.87
  - **R² Score**: ~0.99999957
- The high R² score suggests the model fits the data very well.

---

## Dataset Details

- **Columns**:
  - `squareMeters`: Size of the house in square meters.
  - `numberOfRooms`: Number of rooms in the house.
  - `hasYard`: Indicator if the house has a yard (1 = yes, 0 = no).
  - `hasPool`: Indicator if the house has a pool (1 = yes, 0 = no).
  - `floors`: Number of floors.
  - `price`: Target variable (house price in USD).

---


