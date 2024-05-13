# CropSelector: Optimizing Crop Selection with Machine Learning

## Introduction

CropSelector is a project aimed at assisting farmers in selecting the best crop for their fields based on soil condition. Traditional methods of measuring soil metrics such as nitrogen, phosphorous, potassium levels, and pH value are expensive and time-consuming. By leveraging machine learning techniques, CropSelector provides a solution to predict the optimal crop type for a given soil environment, ultimately maximizing crop yield and enhancing agricultural productivity.

## Dataset Description

The dataset used in this project, named "soil_measures.csv," contains essential soil metrics and corresponding crop types. The features include:

- "N": Nitrogen content ratio in the soil
- "P": Phosphorous content ratio in the soil
- "K": Potassium content ratio in the soil
- "pH": pH value of the soil
- "crop": Categorical values representing various crop types (target variable)

## Project Goals

1. Build multi-class classification models to predict the type of crop based on soil metrics.
2. Identify the single most important feature for predictive performance.
3. Assist farmers in selecting the best crop for their fields by providing actionable insights derived from machine learning analysis.

## Results

- Accuracy achieved: 61.14%
- Best predictive feature: Potassium content ratio ("K")

## Conclusion

CropSelector demonstrates the potential of machine learning in optimizing crop selection and contributing to sustainable agricultural practices. By accurately predicting the optimal crop type based on soil condition, farmers can make informed decisions to maximize crop yield and productivity.

## Future Directions

- Refinement of classification models for improved predictive performance.
- Integration of real-time soil data collection and analysis for dynamic crop recommendations.
- Expansion of features and datasets for enhanced accuracy and applicability.
