# California-Housing-Regression-Analysis
Implementation and comparison of regression algorithms on the California Housing Dataset using Python and Scikit-Learn. Includes preprocessing, model evaluation, and performance comparison.
The objective of this assignment is to evaluate regression techniques in supervised learning by applying them to the California Housing dataset.

## Dataset Used
- Dataset: California Housing Dataset
- Source: sklearn.datasets.fetch_california_housing()
- Target Variable: Median House Value

The dataset contains housing-related features of districts in California such as:
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

## Preprocessing Steps

1. Loaded dataset using fetch_california_housing()
2. Converted dataset into Pandas DataFrame
3. Checked and handled missing values
4. Split data into training and testing sets (80-20 split)
5. Applied StandardScaler for feature scaling

Feature scaling was necessary especially for:
- Linear Regression
- Support Vector Regressor (SVR)


##  Regression Algorithms Implemented

1. Linear Regression  
2. Decision Tree Regressor  
3. Random Forest Regressor  
4. Gradient Boosting Regressor  
5. Support Vector Regressor (SVR)


##  Evaluation Metrics Used

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

These metrics were used to compare model performance.


## Model Comparison

The best performing model was selected based on:
- Highest R² Score
- Lowest MSE and MAE

The worst performing model was identified based on:
- Lowest R² Score
- Higher error values


##  Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn

##  Conclusion

Different regression algorithms were applied to predict housing prices.  
Ensemble methods like Random Forest and Gradient Boosting generally performed better than basic linear models.

