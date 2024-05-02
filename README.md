# Effects of Water Stress on Crop Yield and Yield Estimation using Machine Learning

## Overview

In this study, the impact of water stress on crop yield, particularly focusing on wheat crops in the Punjab region of India, is analyzed. Exploratory Data Analysis (EDA) techniques are employed to study weather data, and machine learning models are implemented for yield prediction. The study aims to provide insights into the relationship between water stress and crop yield and to achieve high accuracy in yield prediction using machine learning techniques.

## Dataset

- The dataset comprises weather data from the Punjab region, including variables such as temperature, precipitation, soil moisture, and crop yield.
- Data preprocessing techniques are applied to prepare the dataset for machine learning models.

## Exploratory Data Analysis (EDA)

- Visualizations are generated to analyze the relationship between water stress indicators (such as precipitation, soil moisture) and crop yield.
- Insights are drawn from the EDA process to understand the effects of water stress on crop yield.

## Machine Learning Models

### Linear Regression

- A simple linear regression model is trained to predict crop yield based on weather variables.
- Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) are calculated to assess model performance.

### Random Forest Regressor

- A Random Forest regression model is employed to capture nonlinear relationships between weather variables and crop yield.
- Model performance is evaluated using similar metrics as linear regression.

### Polynomial Regression

- Polynomial regression models of varying degrees are tested to capture complex relationships between weather variables and crop yield.
- The performance of polynomial regression models is compared to linear and random forest regression.

## Results and Insights

- The study provides valuable insights into the impact of water stress on crop yield in the Punjab region.
- Machine learning models demonstrate high accuracy in yield prediction, with various models offering different trade-offs between complexity and performance.
- Recommendations are provided for stakeholders in agriculture and policymaking based on the study findings.

## Usage

1. **Data Collection**:
   - Gather weather and crop yield data from reliable sources, focusing on the Punjab region of India.

2. **Data Preprocessing**:
   - Preprocess the data to handle missing values, scale features, and prepare it for machine learning models.

3. **EDA**:
   - Perform exploratory data analysis to understand the relationship between water stress indicators and crop yield.

4. **Model Training**:
   - Train machine learning models such as linear regression, random forest regression, and polynomial regression on the preprocessed data.

5. **Evaluation**:
   - Evaluate model performance using appropriate metrics and compare the performance of different models.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow (for Polynomial Regression)

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Rachit Patel
