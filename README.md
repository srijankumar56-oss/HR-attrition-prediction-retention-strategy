# HR Attrition Prediction & Retention Strategy Optimization

Predictive analytics project designed to identify employee attrition risk, optimize retention interventions, and reduce replacement costs using KNIME-based machine learning workflows.

## Business Problem

Employee attrition creates operational disruption, hiring costs, productivity losses, and knowledge leakage.

The objective of this project was to proactively identify employees at risk of attrition and build targeted retention strategies using predictive analytics.

## Project Objectives

- Predict employee attrition risk
- Compare multiple classification models
- Optimize intervention strategy
- Reduce misclassification cost
- Prioritize retention investment

- ## Dataset Overview

Development Dataset:
- 1220 employee records

Scoring Dataset:
- 250 employees

Target Variable:
- Attrition (Yes / No)

Class Distribution:
- Attrition = No → 1023
- Attrition = Yes → 197


## Workflow Architecture

![Workflow](screenshots/workflow.png)

## Exploratory Data Analysis

### Target Variable Distribution

![Count](screenshots/target-count.png)

![Proportion](screenshots/target-proportion.png)

### Categorical Analysis

![Overtime](screenshots/over_time_attrition.png)

![Department](screenshots/dept_wise_attrition.png)

![Job Level](screenshots/Job_level_attrition.png)

### Numeric Analysis

![Income](screenshots/monthly-income-boxplot.png)

![Distance](screenshots/distance-from-home-boxplot.png)

### Correlation Analysis

![Heatmap](screenshots/correlation-heatmap.png.png)


## Model Development & Evaluation

Models Compared:

- Decision Tree
- Random Forest
- Gradient Boosted Trees (GBT)

### Performance Metrics

![Metrics](screenshots/roc_curve.png)

![Metrics](screenshots/scoring_metrices.png)

![Table](screenshots/Model_performance.png)

### Confusion Matrices

![RF](screenshots/RF_confusion_Matrix.png)

![GBT](screenshots/GBT-confusion_Matrix.png)

## Feature Importance

Key drivers influencing employee attrition:

- Overtime
- Stock Option Level
- Monthly Income
- Job Level
- Total Working Years

![Importance](screenshots/Feature_importance.png)

## Retention Strategy

Employees were segmented using:

- Attrition Risk
- Employee Potential

This enabled prioritization of retention interventions and investment allocation.

![Risk Matrix](screenshots/Risk_potential_Matrix.png)

![Risk Matrix](screenshots/Retention_cost_scenarios.png)


## Cost Optimization

GBT achieved the lowest misclassification cost and was selected as the final model.

![Cost](screenshots/Misclassification_Cost.png)


## Tools Used

- KNIME Analytics Platform
- Excel
- Classification Models
- Feature Engineering
- Predictive Analytics

- ## Repository Structure

workflow/
presentation/
screenshots/
data/
outputs/



