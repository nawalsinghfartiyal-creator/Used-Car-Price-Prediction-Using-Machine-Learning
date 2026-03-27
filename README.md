# Used-Car-Price-Prediction

## 📌 Project Overview

The price of a used car depends on several factors such as the vehicle's age, mileage, fuel type, transmission type, and number of previous owners. Accurately estimating the resale value of a car can be challenging without analyzing historical data.
This project aims to develop a machine learning model that predicts the selling price of used cars using various vehicle attributes. By applying data preprocessing, exploratory data analysis, and regression algorithms, the project demonstrates how machine learning can be used to solve real-world pricing problems.Multiple regression models were trained and evaluated, and Random Forest Regression achieved the best performance, providing reliable and accurate price predictions


## 🎯 Objectives

The main objectives of this project are:

  - To analyze factors affecting used car prices
  - To perform data cleaning and preprocessing
  - To conduct Exploratory Data Analysis (EDA) to understand patterns in the dataset
  - To train and evaluate multiple machine learning regression models
  - To select the best performing model for predicting car prices


##  📂 Dataset
  The dataset contains several features related to used cars:

- `Year` – Manufacturing year of the car  
- `Present_Price` – Current showroom price  
- `Selling_Price` – Selling price of the used car  
- `Kms_Driven` – Total kilometers driven  
- `Fuel_Type` – Petrol, Diesel, or other fuel types  
- `Transmission` – Manual or Automatic transmission
       


## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure of the dataset and identify important relationships between different variables.
      
  - **Average Selling Price by Fuel Type**

    Analysis of selling prices by fuel type showed that diesel vehicles often have higher resale values compared to petrol vehicles, 
    likely due to their fuel efficiency and demand in the used car market 

   - **Distribution of Transmission Types**

     The dataset contains a higher proportion of manual transmission vehicles compared to automatic vehicles, indicating that manual
      cars dominate the dataset

   - **Relationship Between Year and Selling Price**

     Cars manufactured in more recent years generally have higher selling prices, which reflects the natural depreciation of vehicles
      over time

  - **Owner vs Kilometers Driven**
      
      ehicles with more previous owners tend to have higher kilometers driven, which is expected because the car has been useby
      multiple individuals

  - **Kilometers Driven Trend by Fuel Type**

    The trend analysis of kilometers driven across different fuel types helps understand vehicle usage patterns and driving behavior
      over time

  - **Present Price Trend Over Years**

    The showroom price of cars generally increases with newer manufacturing years, reflecting technological improvements and rising
      vehicle costs


## ⚙️ Methodology
  
  The project follows a structured machine learning workflow to build an effective price prediction model.

  -  **Data Collection**

     The dataset containing used car information was obtained from a publicly available dataset. It includes several features
          related to vehicle specifications and prices

  -  **Data Cleaning**

      The dataset was inspected to identify and handle potential issues such as:

     -> Missing values

     -> Duplicate records

      -> Incorrect data formats

     Cleaning the dataset ensured that the data was suitable for analysis and model training

  - **Data Preprocessing**

    Since machine learning models require numerical input, categorical variables such as Fuel Type and Transmission were converted
          into numerical values using encoding techniques

  - **Exploratory Data Analysis**

    EDA was performed to identify patterns, relationships, and trends within the dataset. Visualization techniques helped reveal
          insights about how different factors influence car prices.

  - **Model Training**

    Multiple regression algorithms were trained to predict used car prices

  - **Model Evaluation**

    Each model was evaluated using standard regression metrics to determine its prediction accuracy
          
  - **Model Selection**

    The model with the best evaluation performance was selected as the final model


    
## 🧠 Machine Learning Models Used
  
The following regression algorithms were implemented and compared:

1.  **Linear Regression**
 
    A basic regression model used as a baseline to understand the relationship between input features and the selling price.

2.  **Random Forest Regression**
 
    An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting

**Among these models, _Random Forest Regression_ produced the best results**



## 📈 Model Evaluation Metrics

  To evaluate the performance of each model, the following regression metrics were used:

  - **Mean Absolute Error (MAE)**:
    Measures the average absolute difference between predicted and actual values

  - **Mean Squared Error (MSE)**:
    Measures the average squared difference between predictions and actual values

  - **Root Mean Squared Error (RMSE)**:
    Square root of MSE, providing error in the same unit as the target variable

  - **R² Score**:
    Indicates how well the model explains the variance in the data



## 📊 Model Performance & Results

#### Key Observations

  - _Linear Regression_ provided a basic prediction baseline but struggled with complex relationships in the dataset.

  - _Decision Tree Regression_ improved performance by capturing nonlinear patterns.

  - _Random Forest Regression_ achieved the highest prediction accuracy and lowest error, making it the best performing model

    
#### Final Model

The **_Random Forest Regression_** model was selected as the final model because it:

  - Achieved the highest R² score
  - Produced the lowest prediction errors
  - Demonstrated strong generalization capability
    

        
## 🛠️ Technologies Used

The project was implemented using the following tools and libraries:

  - **Python**

  - **Pandas**

  - **NumPy**

  - **Matplotlib**

  - **Seaborn**

  - **Scikit-learn**

  - **Jupyter Notebook**



## 📌 Conclusion

This project demonstrates how **machine learning techniques can be applied to predict used car prices based on vehicle characteristics**.
Through data cleaning, exploratory data analysis, feature engineering, and model evaluation, important patterns influencing car prices were identified. Among the tested models, Random Forest Regression performed the best, delivering the most accurate predictions.
The project highlights the practical use of data science in solving real-world problems such as vehicle price estimation. With further improvements such as model deployment and additional data sources, the system could be developed into a fully functional car price prediction application.
