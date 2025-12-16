# Post-Click Conversion Prediction

## Problem Statement
The objective of this project is to predict whether a user will convert after engaging with a digital marketing campaign using post-click behavioral data and user attributes.

## Dataset
Causal Digital Marketing Campaign Dataset [(Kaggle)](https://www.kaggle.com/datasets/rahuljangir78/causal-digital-marketing-campaign-dataset)

## Target Variable
- `conversion` (1 = converted, 0 = not converted)

## Approach
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature selection
- Random Forest classification
- Handling class imbalance
- Threshold tuning for business optimization

## Model Used
- Random Forest Classifier

## Evaluation Metrics
- Precision
- Recall
- F1-score
- ROC-AUC

## Key Results
- Conversion recall improved to ~64% after threshold tuning
- Engagement features such as clicks and impressions were the most important predictors

## Conclusion
The model effectively identifies potential converters in a post-click marketing scenario and can be used for retargeting and budget optimization decisions.

## Future Improvements 
- Cost-sensitive learning
- Uplift modeling
- Feature calibration

