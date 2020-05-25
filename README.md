# ill-patient-analysis

This time we focus on predict the patient's  mean-MAP (mean arterial pressure) and mean-HR (mean heart rate) given a key (for a patientid and a period of time). 

The training data contains patient id, patient key, age, and other features (x1, x2, etc.) where we can't know the meaning through the column names.

## Analytic tools

We use python to do data analysis. 

In the feature engineering part, we tried upsampling and downsampling, clustering, mean encoding/target encoding  , aggregation and missing value imputation. In the modeling part, we tried using XGBoost, Random Forest, Light-BGM model.

The best validation score is 0.92711.
