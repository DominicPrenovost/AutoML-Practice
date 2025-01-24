# Summary of 7_Xgboost_GoldenFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.15
- **max_depth**: 8
- **min_child_weight**: 1
- **subsample**: 1.0
- **colsample_bytree**: 1.0
- **eval_metric**: auc
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

103.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.502484 | nan           |
| auc       | 0.875619 | nan           |
| f1        | 0.785004 |   0.271664    |
| accuracy  | 0.798942 |   0.556853    |
| precision | 0.99446  |   0.996783    |
| recall    | 1        |   2.81709e-06 |
| mcc       | 0.595919 |   0.556853    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.502484 |  nan        |
| auc       | 0.875619 |  nan        |
| f1        | 0.777127 |    0.556853 |
| accuracy  | 0.798942 |    0.556853 |
| precision | 0.807967 |    0.556853 |
| recall    | 0.748554 |    0.556853 |
| mcc       | 0.595919 |    0.556853 |


## Confusion matrix (at threshold=0.556853)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3477 |              646 |
| Labeled as 1 |              913 |             2718 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
