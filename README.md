# Used-Car-Price-Prediction

📌 Project Overview

The price of a used car depends on several factors such as the vehicle's age, mileage, fuel type, transmission type, and number of previous owners. Accurately estimating the resale value of a car can be challenging without analyzing historical data.
This project aims to develop a machine learning model that predicts the selling price of used cars using various vehicle attributes. By applying data preprocessing, exploratory data analysis, and regression algorithms, the project demonstrates how machine learning can be used to solve real-world pricing problems.Multiple regression models were trained and evaluated, and Random Forest Regression achieved the best performance, providing reliable and accurate price predictions.


🎯 Objectives

  The main objectives of this project are:

            1. To analyze factors affecting used car prices
            2. To perform data cleaning and preprocessing
            3. To conduct Exploratory Data Analysis (EDA) to understand patterns in the dataset
            4. To train and evaluate multiple machine learning regression models
            5. To select the best performing model for predicting car prices


📂 Dataset

  The dataset contains several features related to used cars:

              -> Year – Manufacturing year of the car
              -> Present_Price – Current showroom price of the car
              -> Selling_Price – Selling price of the used car
              -> Kms_Driven – Total kilometers driven
              -> Fuel_Type – Petrol, Diesel, or other fuel types
              -> Transmission – Manual or Automatic transmission


📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure of the dataset and identify important relationships between different variables.
      
      1.Average Selling Price by Fuel Type
      Analysis of selling prices by fuel type showed that diesel vehicles often have higher resale values compared to petrol vehicles, 
      likely due to their fuel efficiency and demand in the used car market 

      2. Distribution of Transmission Types
      The dataset contains a higher proportion of manual transmission vehicles compared to automatic vehicles, indicating that manual
      cars dominate the dataset

      3. Relationship Between Year and Selling Price
      Cars manufactured in more recent years generally have higher selling prices, which reflects the natural depreciation of vehicles
      over time

      4. Owner vs Kilometers Driven
      Vehicles with more previous owners tend to have higher kilometers driven, which is expected because the car has been useby
      multiple individuals

      5. Kilometers Driven Trend by Fuel Type
      The trend analysis of kilometers driven across different fuel types helps understand vehicle usage patterns and driving behavior
      over time

      6. Present Price Trend Over Years
      The showroom price of cars generally increases with newer manufacturing years, reflecting technological improvements and rising
      vehicle costs


⚙️ Methodology

  The project follows a structured machine learning workflow to build an effective price prediction model.

          1. Data Collection
          The dataset containing used car information was obtained from a publicly available dataset. It includes several features
          related to vehicle specifications and prices

          2. Data Cleaning
          The dataset was inspected to identify and handle potential issues such as:
          -> Missing values
          -> Duplicate records
          -> Incorrect data formats
          Cleaning the dataset ensured that the data was suitable for analysis and model training

          3. Data Preprocessing
          Since machine learning models require numerical input, categorical variables such as Fuel Type and Transmission were converted
          into numerical values using encoding techniques

          4. Exploratory Data Analysis
          EDA was performed to identify patterns, relationships, and trends within the dataset. Visualization techniques helped reveal
          insights about how different factors influence car prices.

          5. Model Training
          Multiple regression algorithms were trained to predict used car prices

          7. Model Evaluation
          Each model was evaluated using standard regression metrics to determine its prediction accuracy
          
          8. Model Selection
          The model with the best evaluation performance was selected as the final model









        
