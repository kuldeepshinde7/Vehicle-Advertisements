# Vehicle-Advertisements analysis
This project analyzes a dataset of vehicle advertisements to address three critical areas: Price Prediction, User Segmentation, and Geographical Analysis of Demand and Supply. The goal is to build predictive models, perform segmentation, and derive insights to inform business strategies.

# Dataset Description:
The dataset contains information on vehicle advertisements with the following key columns:

Ad Details: ad_title, ad_description, details, slug, title, type
Pricing: price
Dates: timestamp, posted_date, deactivation_date
Categorization: category, parent_category
Location: location, geo_region, area
Delivery Options: is_delivery_free, is_doorstep_delivery, is_dsd_applicable
Advertiser Details: is_member, is_authorized_dealer, is_featured_member, is_verified, membership_level, member_since
Other Features: properties, user

# Sections of Analysis
# 1. Price Prediction
# Objective: Develop a predictive model to estimate vehicle prices based on advertisement features.

# Key Steps:
1)Data Cleaning & Preprocessing:
2)Handle missing values.
3)Encode categorical variables and normalize numerical features.
4)Feature Selection:
5)Perform correlation analysis.
6)Apply Recursive Feature Elimination (RFE) or Lasso Regression for feature selection.
7)Model Training:
8)Train at least three regression models and evaluate using cross-validation.
9)Hyperparameter Tuning:
10)Optimize hyperparameters using Grid Search or Random Search.
11)Model Evaluation:
12)Compare models using RMSE, MAE, and R² metrics.

# Deliverables:
A detailed report on data preprocessing and feature selection.
Performance metrics of trained models.
A final price prediction model with tuned hyperparameters.
Discussion on model strengths and weaknesses.

# 2. User Segmentation
# Objective: Segment users based on advertisement behaviors and characteristics.

Key Steps:
1)Data Preprocessing:
2)Handle missing values.
3)Encode categorical variables.
4)Feature Selection:
5)Apply PCA if necessary.
6)Select relevant features for clustering.
7)Clustering:
8)Use K-means clustering to segment users.
9)Evaluate clusters using the Elbow Method and Silhouette Score.
10)Cluster Analysis:
11)Interpret and describe each cluster’s characteristics.

# Deliverables:
A detailed report on data preprocessing and feature selection.
Visualizations of clusters and their characteristics.
Descriptions of user segments with potential business implications.

# 3. Geographical Analysis of Demand and Supply
# Objective: Analyze the geographical distribution of vehicle advertisements to understand demand and supply patterns.

Key Steps:
1)Data Preprocessing:
2)Handle missing values.
3)Encode geographical variables.
4)Geographical Analysis:
5)Visualize advertisement distribution across regions.
6)Identify areas with high demand and supply.
7)Temporal Analysis:
8)Examine demand and supply variations over time and identify seasonal trends.
9)Modeling Demand and Supply:
10)Build a regression model to predict demand and supply based on geographical and temporal features.

# Deliverables:
Visualizations of geographical and temporal trends.
A detailed report on findings from the analysis.
Performance metrics of the demand and supply prediction model.
Insights and recommendations.
