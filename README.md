# Zillow Housing Price Analysis for San Francisco Bay Area

## Project Overview

This project provides a comprehensive analysis of housing prices in the San Francisco Bay Area, leveraging a dataset from Zillow. The analysis focuses on predicting housing prices and understanding the factors influencing them, such as square footage, bedroom count, and location. Various machine learning models were evaluated, and the XGBoost model was identified as the most effective for predicting housing prices.

### Key Objectives
- **Predict Housing Prices**: Develop models to forecast housing prices based on property features.
- **Analyze Market Trends**: Study how factors like property size and location affect price dynamics.
- **Identify Key Determinants**: Investigate critical factors such as square footage, zip code, and latitude that significantly impact property values.

### Data Description
- **Dataset**: 20,000 samples from the San Francisco Bay Area, with information on property size, bedroom count, location, and sale price from 2003-2006.
- **Features**: Key variables include square footage, number of bedrooms, lot size, zip code, and geographic coordinates.

### Models Implemented
- **Linear Regression**: Baseline model for simple relationships.
- **Random Forest Regressor**: Improved performance but with room for enhancement.
- **Support Vector Regressor (SVR)**: Handled non-linear relationships but performed poorly on this dataset.
- **Gradient Boosting**: Showed strong results in capturing complex relationships.
- **XGBoost**: Achieved the highest predictive accuracy with an R² score of 0.68 and was the most effective model.

### Results
- **Best Model**: XGBoost emerged as the top-performing model with a balance of accuracy and complexity.
- **Key Influencers**: Square footage, number of bedrooms, zip code, and latitude were identified as significant factors affecting housing prices.

### Tools & Libraries
- **Python**: For data analysis and modeling.
- **Pandas**: For data manipulation.
- **Seaborn & Matplotlib**: For data visualization.
- **Scikit-learn & XGBoost**: For machine learning model implementation.

### Conclusion
This project successfully analyzed and predicted housing prices in the San Francisco Bay Area using machine learning techniques. XGBoost was identified as the most accurate model, and the insights derived from this analysis can help inform buyers, sellers, and investors about market trends and key factors influencing property values.

