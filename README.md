# lungcancer-prediction
## Lung Cancer Prediction Model
This project focuses on determining the likelihood of a patient having lung cancer based on 15 parameters:

- GENDER
- AGE
- SMOKING
- YELLOW_FINGERS
- ANXIETY
- PEER_PRESSURE
- CHRONIC DISEASE
- FATIGUE
- ALLERGY
- WHEEZING
- ALCOHOL CONSUMING
- COUGHING
- SHORTNESS OF BREATH
- SWALLOWING DIFFICULTY
- CHEST PAIN
## Data Source
This dataset, sourced from Kaggle, consists of 309 rows and 16 columns, each representing specific health-related parameters used to assess the likelihood of a patient having lung cancer.
## Methodology
The dataset was preprocessed by eliminating null values, duplicate entries, and features with low correlation to the lung cancer outcome. These cleaning steps enhanced the model’s predictive accuracy.
## Result
Visualizations generated with Seaborn offer valuable insights into potential risk factors associated with lung cancer. A Support Vector Machine (SVM) model was trained using health-related attributes and achieved an accuracy of 88.4% in predicting the presence of lung cancer.


