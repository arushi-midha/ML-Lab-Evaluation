# ML-Lab-Evaluation

**Name**: Arushi Midha
**Roll Number**: 102203916

This project evaluates the performance of multiple regression models on a dataset. It includes an analysis of various models and a visualization of predicted vs. actual values of the best model.  Metrics such as MAE, MSE, RMSE, R², RMSLE, and MAPE have been used to assess model performance.

## Dataset
Fuel_Cell_Performance_data_Full.csv
(Uploaded in the repository)

## Workflow
1. **Dataset Preparation**:
- Dataset split into training and testing sets (70/30).
- Missing values handled and features preprocessed.

2. **Model Training**:
- Multiple regression models trained using PyCaret.
- Metrics compared to identify the best model.

3. **Analysis Plots**:
- Visualizes the relationship between true values and predicted values.
- Visualizes the training and cross validation scores.

## Dependencies
- Python 3.8 or higher
- pyCaret
- pandas

## Results
The best-performing model was **Bayesian Ridge**, achieving:

MAE: 0.2603    
MSE: 0.0996    
RMSE: 0.3143    
R²: 0.6565

![image](https://github.com/user-attachments/assets/4a1f7d7b-801b-49b6-8a3f-d094009d9914)



Prediction Error plot for Bayesian Ridge

![image](https://github.com/user-attachments/assets/a40c03e6-d1ca-44e0-9857-54500ebf1146)



Learning Curve Plot for Bayesian Ridge

![image](https://github.com/user-attachments/assets/7ea14233-18e3-43c2-a161-fb307acc4c9f)


## Summary
A total of 20 models were evaluated. The Bayesian Ridge (br) model emerged as the best performer based on the lowest Mean Absolute Error (MAE) of 0.2603, the lowest Root Mean Squared Error (RMSE) of 0.3143, and the highest R² score of 0.6565.    
In contrast, models like the Dummy Regressor and K Neighbors Regressor performed poorly, with negative R² values, indicating inadequate predictions.




