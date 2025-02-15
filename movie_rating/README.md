# Movie Rating Prediction  

This project is a machine learning model that predicts the rating of a movie based on various features like genre, director, and actors. The model uses regression techniques to estimate ratings accurately.  

## Dataset  
- The dataset contains information about movies, including their genre, director, actors, and ratings.  
- The data is preprocessed using feature encoding, scaling, and dimensionality reduction before training the model.  

## Project Files  
- movie_rating.ipynb → Jupyter Notebook containing data analysis, feature engineering, model training, and evaluation.  
- ridge_regression_model.pkl → Trained Ridge Regression model for predicting movie ratings.  
- scaler.pkl → StandardScaler object used to normalize the dataset before training.  
- pca.pkl → PCA object used for dimensionality reduction to improve performance.  

## How to Use  
1. Open movie_rating.ipynb in Jupyter Notebook.  
2. Run all the cells to preprocess the data, train the model, and evaluate performance.  
3. Use ridge_regression_model.pkl along with scaler.pkl and pca.pkl to make predictions on new movie data.  

## Results  
The model was trained using Ridge Regression and achieved the following performance metrics:  
- Mean Absolute Error (MAE): 0.5936  
- Mean Squared Error (MSE): 0.9314  
- Root Mean Squared Error (RMSE): 0.9651  

## Author  
Ahmed7Rafat - Data Science Intern
