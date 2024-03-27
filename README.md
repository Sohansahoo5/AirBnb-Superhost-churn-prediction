# AirBnb-Superhost-churn-prediction
# Executive Overview

In a strategic shift towards advanced data-driven decision-making, we at Team 12 embarked on an initiative to predict and understand the churn of Airbnb Superhosts. This predictive modeling project aimed to empower Airbnb to maintain the high-quality standards set by their Superhost program, thereby ensuring guest satisfaction and optimizing the platform's overall performance. We developed a model that could predict whether Superhosts would retain their status during the next evaluation period, providing actionable insights for Airbnb to proactively engage with at-risk Superhosts.

# Exploratory Data Analysis (EDA) Insights:

Our EDA provided a comprehensive understanding of the factors influencing Superhost churn:
Business Impact: We quantified the business impact of Superhost churn, noting an average loss of revenue (12%), reviews (21%), and occupancy (18%) when a Superhost loses their status.

Revenue and Saturation: Our analysis also observed that Superhost properties generate higher revenue than non-Superhost properties, and the rate of net change in Superhosts has decreased, indicating potential market saturation.

# Data Preprocessing and Preparation:
The preprocessing phase involved a structured approach to creating a clean and robust dataset:

Data Cleaning: We dealt with over 30% missing values and diverse columns requiring distinct aggregation methods.

Class Imbalance: Our dataset exhibited a substantial imbalance, which we addressed using the Synthetic Minority Over-sampling Technique (SMOTE) to create a more balanced training environment for our models.

# Predictive Modeling:

The predictive modeling phase involved several critical steps:

Data Aggregation and Variable Selection: We aggregated data such as previous revenue, number of reviews, ratings, and occupancy levels, identifying key variables influencing churn.

Model Comparison: Logistic Regression and Random Forest were benchmarked against each other.

Model Selection: The Logistic Regression model was selected for its high sensitivity and ease of interpretability, despite a marginal sacrifice in overall accuracy.

# Model Performance:

The Logistic Regression model demonstrated high performance:

Cost vs. Accuracy: 234 out of 285 actual churned hosts were correctly identified, which indicates the model's strong predictive capability.

Sensitivity and Interpretability: The model prioritized reducing the false negative rate, capturing hosts with a high propensity to churn more effectively than the Random Forest model. This balance was chosen to ensure that Airbnb could take proactive measures with those most at risk, even if it meant accepting a slightly lower overall accuracy.

# Strategic Implications and Recommendations:

The findings from this project are highly actionable:

Proactive Engagement: Airbnb can use the model to pinpoint and support Superhosts in danger of churn, ensuring the sustainability of the Superhost program.

Superhost Support: Recommendations include providing operational auditing services to current Superhosts to help them maintain their status, and planning for a balance between Superhosts and non-Superhost listings.
