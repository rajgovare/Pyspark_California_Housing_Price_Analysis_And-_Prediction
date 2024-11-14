---
# California Housing Data Analysis and Prediction Using PySpark

## Overview
This project involves a comprehensive analysis and predictive modeling of the California Housing dataset using Apache Spark (PySpark). The goal of the project is to derive insights from the dataset through exploratory data analysis (EDA) and to build a predictive model to estimate house prices based on various features, such as location, median income, and housing characteristics.

The project showcases skills in big data analytics, distributed computing, data wrangling, and machine learning, making it an ideal addition to your resume for roles related to data analysis, data science, or machine learning engineering.

---
## Methodology
This project follows a structured approach, including the following key steps:

1. **Data Collection & Preprocessing**:
   - Loaded California housing training and test datasets using PySpark.
   - Conducted initial data exploration to understand the dataset structure.
   - Cleaned and preprocessed the data, handling missing values and preparing features for analysis.
   - Used `VectorAssembler` to transform the feature columns into a single vector column for machine learning models.

2. **Exploratory Data Analysis (EDA)**:
   - Performed in-depth analysis using SQL queries in PySpark to extract insights and identify patterns in the data.
   - Analyzed various factors affecting house prices, such as location, income levels, housing age, and population density.

3. **Predictive Modeling**:
   - Implemented a Gradient Boosted Trees (GBT) regression model to predict house prices.
   - Applied cross-validation and hyperparameter tuning using a grid search approach to optimize the model.
   - Evaluated model performance using metrics such as Root Mean Squared Error (RMSE), R² score, and Mean Absolute Error (MAE) on both validation and test datasets.
     
---

## Analysis Performed
Below are the key analyses performed using PySpark:

1. **Average House Value by Median Income Bracket**:
   - Grouped data by median income to determine how income levels affect house prices.

2. **Maximum and Minimum House Values by Location**:
   - Analyzed the highest and lowest house values in different housing blocks based on their geographical coordinates.

3. **House Value Analysis for Older Houses**:
   - Calculated average house values for houses older than 50 years to understand their value retention.

4. **House Value by Proximity to the Ocean**:
   - Categorized houses based on longitude to determine if proximity to the ocean impacts house prices.

5. **Average Number of Rooms by Housing Age**:
   - Analyzed the relationship between the age of the house and the average number of rooms.

6. **Top Locations with the Highest Median Income**:
   - Identified the top 10 locations with the highest income levels.

7. **Correlation Between Population and House Value**:
   - Conducted a correlation analysis between population density and median house value to explore any significant relationships.

8. **House Value by Income Level (Low, Medium, High)**:
   - Classified houses based on income levels and analyzed how these categories influence house prices.

9. **Distribution of Houses by Age Groups**:
   - Categorized houses into new, middle-aged, and old groups based on their age to understand their distribution.

10. **Average Number of Bedrooms Per Household**:
    - Calculated the average number of bedrooms per house to analyze housing density.

11. **House Value by Latitude and Longitude**:
    - Performed spatial analysis to find the regions with the highest median house values.

12. **Households with More Than 4 Persons Per Household**:
    - Analyzed the distribution of large households based on the population-to-household ratio.

13. **House Density Analysis (Rooms per Area)**:
    - Examined housing density by calculating the number of rooms relative to housing age.

---
## Results
   The analyses provide valuable insights into factors influencing housing prices in California, including income, age of housing, population density, and geographical location. The model's ability to predict housing values was enhanced by carefully considering these factors, making it a useful tool for understanding and forecasting real estate trends in the region.

   Also,The predictive analysis of California housing data using Gradient Boosted Trees (GBT) Regressor demonstrated strong performance on both the validation and test datasets.
Key evaluation metrics such as RMSE (Root Mean Squared Error), R² (Coefficient of Determination), and MAE (Mean Absolute Error) were computed to assess the model's accuracy:

- **Validation Metrics:** The model showed a low RMSE, indicating relatively small prediction errors, and a high R², suggesting that it explained a significant portion of the variance in the housing prices. The MAE was also within an acceptable range, indicating that the average magnitude of errors was reasonable.

- **Test Metrics:** The performance on the test set was consistent with the validation results, confirming that the model generalized well to unseen data. Similar trends in RMSE, R², and MAE were observed on the test set, suggesting robustness and reliability.

  The analyses provide valuable insights into factors influencing housing prices in California, including income, age of housing, population density, and geographical location. The model's ability to predict housing values was enhanced by carefully considering these factors, making it a useful tool for understanding and forecasting real estate trends in the region.

  ---
## Key Findings
- **Income Levels and House Prices**: Higher income levels are strongly correlated with higher house prices, indicating that wealthier areas tend to have more expensive properties.
- **Proximity to Ocean**: Houses closer to the ocean tend to have significantly higher median values, suggesting that location plays a crucial role in property valuation.
- **Age of Housing**: Older houses in certain regions still maintain high values, particularly in areas with desirable locations.
- **Population Density**: There is a noticeable relationship between population density and house values, where areas with higher populations tend to have varied house prices based on available amenities.
---
## Project Significance
This project demonstrates proficiency in:
- **Big Data Tools**: Utilization of Apache Spark for large-scale data processing.
- **Data Analysis**: Performing complex SQL queries to extract insights.
- **Machine Learning**: Building and optimizing regression models using PySpark's MLlib.
- **Predictive Analytics**: Applying advanced techniques like Gradient Boosting Trees to predict continuous variables.
---
## Conclusion
This project successfully demonstrates how to leverage big data tools and machine learning techniques to analyze and predict house prices.
The insights gained can be valuable for real estate market analysis, investment strategies, and urban planning.

---
