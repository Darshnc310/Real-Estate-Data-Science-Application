# Real-Estate-Data-Science-Application

This comprehensive project aimed at predicting real estate prices and offering personalized property recommendations. By leveraging data from 99acres.com, the project encompasses data collection, preprocessing, exploratory data analysis, feature engineering, model development, and the implementation of a recommender system.

(1) Project Overview:

    The primary objectives of this project include:
    Data Collection: Utilizing web scraping techniques to gather property listings from 99acres.com, focusing on attributes such as property type, location, size, price, and amenities.
    Data Preprocessing: Cleaning and preparing the collected data by handling missing values, detecting and treating outliers, and transforming data types to ensure consistency and reliability.
    Exploratory Data Analysis (EDA): Conducting univariate, bivariate, and multivariate analyses to uncover patterns and relationships within the data, providing insights into factors influencing property prices.
    Feature Engineering and Selection: Creating new features and selecting the most relevant ones to enhance the predictive power of the models.
    Model Development: Building and evaluating various machine learning models, including Random Forest Regressor, Linear Regressor, and Decision Tree Regressor, to accurately predict property prices.
    Recommender System: Implementing a content-based recommender system that suggests properties aligning with user preferences, considering factors like location, budget, and desired amenities.

(2) Data Collection

    Data was meticulously collected through web scraping of 99acres.com, focusing on properties located in Gurgaon, India. The scraping process extracted essential details such as property type, location, size, price, and available amenities. The acquired data is       stored in CSV format within the data/ directory for subsequent analysis.
  
(3) Data Preprocessing

    The preprocessing phase involved:
      Handling Missing Values: Employing strategies like imputation or removal to address missing data, ensuring the dataset's completeness.
      Outlier Detection and Treatment: Identifying anomalies within the data and applying appropriate treatments to prevent skewed analyses.
      Data Transformation: Converting data types and normalizing distributions to facilitate effective modeling.
      Detailed preprocessing steps are documented in the notebooks/data_preprocessing.ipynb notebook.
      
(4) Exploratory Data Analysis (EDA)

    EDA was performed to gain a deep understanding of the data's structure and underlying patterns. Key analyses include:
      Univariate Analysis: Assessing the distribution of individual variables to identify central tendencies and dispersion.
      Bivariate Analysis: Exploring relationships between pairs of variables to detect correlations and potential causations.
      Multivariate Analysis: Investigating interactions among multiple variables to understand their combined effect on property prices.
      Visualizations and insights from the EDA are available in the notebooks/eda.ipynb notebook.

(5) Feature Engineering and Selection

    To bolster model performance, the project undertook:
      Creation of Interaction Terms: Developing features that capture the interaction between existing variables to model complex relationships.
      Encoding Categorical Variables: Transforming categorical data into numerical formats using techniques like one-hot encoding.
      Feature Scaling: Standardizing numerical features to ensure uniformity across the dataset.
      The feature engineering process is elaborated in the notebooks/feature_engineering.ipynb notebook.

(6) Model Development

    A variety of regression models were developed to predict property prices, including:
      Baseline Models: Establishing simple models to serve as performance benchmarks.
      Advanced Models: Implementing complex algorithms such as Random Forest Regressor, Linear Regressor, and Decision Tree Regressor, followed by hyperparameter tuning to enhance accuracy.
      Model Evaluation: Assessing models using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to determine predictive performance.
      The modeling efforts and evaluations are documented in the notebooks/model_development.ipynb notebook.

(7) Recommender System

    The project features a content-based recommender system designed to suggest properties that align with user-defined preferences. The system takes into account:
      User Criteria: Filtering properties based on specifications such as preferred location, budget constraints, and desired amenities.
      Similarity Measures: Recommending properties that share characteristics with those the user has previously shown interest in.
      Implementation details are provided in the notebooks/recommender_system.ipynb notebook.

(8) Insights Module

    Beyond predictive modeling and recommendations, the project offers an insights module that delivers data-driven analyses, including:
      Market Trends: Evaluating property price fluctuations over time to identify emerging trends.
      Location Analysis: Determining areas that offer optimal value for investment based on current data.
      Feature Impact Assessment: Analyzing how various property attributes influence pricing, aiding stakeholders in decision-making.
      Comprehensive insights are compiled in the reports/insights_report.pdf file.
