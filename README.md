# Rossmann Pharmaceuticals

## Overview

This project aims to forecast sales across multiple Rossmann store locations six weeks into the future using machine learning techniques. The finance team at Rossmann Pharmaceuticals relies on accurate sales predictions to make informed decisions, moving beyond reliance on personal judgment and experience.

## Business Need

- Forecast daily sales for all stores based on various factors, including promotions, competition, holidays, seasonality, and locality.
- Deliver actionable predictions to analysts in the finance team.

## Learning Outcomes

### Skills
- Advanced use of scikit-learn
- Feature engineering
- ML model building and fine-tuning
- CI/CD deployment of ML models
- Python logging and unit testing
- Building dashboards
- Model management and MLOps with DVC, CML, and MLFlow

### Knowledge
- Reasoning with business context
- Data exploration and predictive analysis
- Machine learning concepts, hyperparameter tuning, and model selection

## Project Tasks

### Task 1: Exploration of Customer Purchasing Behavior
- Perform exploratory data analysis (EDA) to understand customer behavior and purchasing patterns.
- Clean the data and visualize findings using appropriate plots.

### Task 2: Prediction of Store Sales
- **Preprocessing**: Transform data for modeling, including feature extraction and scaling.
- **Model Building**: Use scikit-learn pipelines to build regression models (e.g., Random Forest).
- **Loss Function Selection**: Choose and justify an appropriate loss function for sales prediction.
- **Post Prediction Analysis**: Analyze feature importance and estimate prediction confidence intervals.
- **Deep Learning Model**: Build an LSTM regression model for time series forecasting.

### Task 3: Model Serving API Call
- Create a REST API to serve the trained models for real-time predictions.
- Implement logic to preprocess input data and return predictions.

## Cloning the Project

To clone this project, run the following command in your terminal:

```bash
git clone https://github.com/yourusername/rossmann-sales-forecasting.git
```
## License

This project is licensed under the MIT License.
