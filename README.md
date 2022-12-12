# credit_risk_analysis

## Overview
The purpose of this project was to build and evaluate several machine learning models using Supervised Learning to predict credit risk.

## Results

### Naive Random Over Sampling
<img width="830" alt="Screen Shot 2022-12-12 at 4 10 02 AM" src="https://user-images.githubusercontent.com/107594280/207041735-3dd2b6c4-9d02-4f17-878e-0bef2493c10e.png">

- Balanced Accuracy Score: 64%
- Precision Score: 1%
- Recall Score: 66%


### SMOTE Oversampling
<img width="823" alt="Screen Shot 2022-12-12 at 4 11 12 AM" src="https://user-images.githubusercontent.com/107594280/207041911-9b1d16ae-aa0f-43df-b0a1-ea8e1c2d9161.png">

- Balanced Accuracy Score: 65%
- Precision Score: 1%
- Recall Score: 61%


### Undersampling
<img width="565" alt="Screen Shot 2022-12-12 at 4 15 19 AM" src="https://user-images.githubusercontent.com/107594280/207042601-eb26489d-3274-4f99-b791-2c577c0be233.png">

- Balanced Accuracy Score: 65%
- Precision Score: 1%
- Recall Score: 69%


### Combination(Over and Undersampling)
<img width="563" alt="Screen Shot 2022-12-12 at 4 16 35 AM" src="https://user-images.githubusercontent.com/107594280/207042819-f7a1cf9c-156f-4edb-a754-c35b72a3ac37.png">

- Balanced Accuracy Score: 54%
- Precision Score: 1%
- Recall Score: 72%


### Balanced Random Forest Classifier
<img width="813" alt="Screen Shot 2022-12-12 at 4 18 48 AM" src="https://user-images.githubusercontent.com/107594280/207043191-b9a21c07-93b7-4cdf-be63-d6ab87d7709f.png">

- Balanced Accuracy Score: 78%
- Precision Score: 3%
- Recall Score: 67%


### Easy Ensemble AdaBoost Classifier
<img width="818" alt="Screen Shot 2022-12-12 at 4 19 42 AM" src="https://user-images.githubusercontent.com/107594280/207043326-8de3eca7-2ece-4315-9460-dc218a92facf.png">

- Balanced Accuracy Score: 92%
- Precision Score: 9%
- Recall Score: 89%


## Summary
Overall, the Easy Ensemble Classifier proved to be the best model with the largest accuracy score at 92%. It also had the best precision and recall scores as 9% and 89%, meaning that it is the best model to detect credit risk.
