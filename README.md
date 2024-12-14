![University_of_Arizona_logo](https://github.com/user-attachments/assets/3282e738-833a-47ec-a020-efb9d64cde1e)

Overview
This project explores trends in the gaming industry using a dataset containing 4989 rows of data extracted from Kaggle. The primary goal is to analyze and visualize key trends, incorporating advanced data visualization techniques and introducing independently learned methods. The focus is on forecasting gaming industry metrics like revenue, daily active users (DAU), and new registrations while highlighting platform-specific and genre-based insights.

The project emphasizes actionable insights for the gaming industry by leveraging both statistical modeling (Prophet) and machine-learning techniques (XGBoost) to predict trends and provide visual storytelling.

Team Members
Kaushik Kumar
Rohith Singaravelu
Hemanath A
Hemant Kumar B K
Each team member contributed to various stages of the project, including data preprocessing, feature engineering, model development, and creating compelling visualizations.

Project Structure
The project is organized into the following directories:

data/
Contains the Enhanced Gaming Trends Dataset used for analysis. The dataset includes:
Revenue ($)
Daily Active Users (DAU)
New Registrations
Platform and Genre Information
Time-Series Features (Lagged Variables, Moving Averages)
scripts/
Includes R scripts for data cleaning, analysis, and visualization:
Feature engineering with lagged variables and seasonal components.
Forecasting revenue, DAU, and registrations using XGBoost and Prophet.
Generating visualizations for yearly trends, seasonal effects, and feature importance.
outputs/
Contains all generated outputs, including:
Feature importance visualizations.
Revenue and DAU forecasts across platforms (PC, Console, Mobile, VR).
Yearly and seasonal trends by genre.
Model evaluation metrics (RMSE, R²).
docs/
Contains project documentation, including:
Proposal: A detailed outline of the project goals, methodology, and deliverables.
Final Report: A comprehensive analysis of findings.
Poster: A visually appealing summary of the project.
Each folder includes a README.md file explaining its contents in detail.

Goals
The project aims to:

Explore historical trends in the gaming industry using interactive and static visualizations.
Incorporate an advanced R package or technique not covered in the course curriculum to enhance storytelling (e.g., the use of Prophet for seasonal forecasting).
Answer the following research questions:
How have gaming trends evolved over time?
What is the relationship between platform popularity and user ratings?
Which genres are growing in popularity?
Provide actionable insights for industry stakeholders, focusing on platform-specific growth opportunities and optimal timing for game releases.
Methods and Techniques
Data Cleaning and Preprocessing

Removing outliers using the Interquartile Range (IQR) method.
Aggregating weekly data and adding lagged features.
Engineering features like moving averages and seasonal components (sine/cosine transformations).
Modeling

XGBoost: Used for feature importance analysis and revenue forecasting.
Prophet: Used for long-term forecasting and capturing seasonal trends.
Visualization

Yearly revenue trends across genres (Action, Adventure, RPG, etc.).
Platform-specific forecasts for revenue, DAU, and registrations.
Seasonal insights, highlighting spikes during holidays and major game launches.
Deliverables
Proposal

A markdown document (Proposal.qmd) summarizing project objectives, methods, and research questions.
Visualizations and Analysis

High-quality plots, charts, and dashboards illustrating trends, forecasts, and insights.
Final Report

A comprehensive analysis connecting data-driven insights with gaming industry dynamics.
Poster

A visually engaging summary of the project's findings and actionable recommendations.
Key Visualizations (Placeholder for Images)
Feature Importance Chart (XGBoost):

Highlights the impact of lagged features, moving averages, and seasonal components on revenue predictions.
Revenue Trends by Genre:

Shows adjusted yearly revenue trends with notable variations during 2021 and 2022.
Platform-Specific Forecasts:

Revenue and DAU forecasts for PC, Console, Mobile, and VR.
Prophet Seasonal Insights:

Captures cyclical variations in gaming metrics, emphasizing holiday effects.
