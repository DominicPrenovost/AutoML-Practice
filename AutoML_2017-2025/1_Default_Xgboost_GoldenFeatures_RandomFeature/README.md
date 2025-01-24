# Summary of 1_Default_Xgboost_GoldenFeatures_RandomFeature

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
- **max_depth**: 6
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

103.9 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.425947 | nan           |
| auc       | 0.892793 | nan           |
| f1        | 0.793534 |   0.356738    |
| accuracy  | 0.81726  |   0.507583    |
| precision | 0.97561  |   0.994328    |
| recall    | 1        |   1.22094e-05 |
| mcc       | 0.628366 |   0.507583    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.425947 |  nan        |
| auc       | 0.892793 |  nan        |
| f1        | 0.787498 |    0.507583 |
| accuracy  | 0.81726  |    0.507583 |
| precision | 0.812263 |    0.507583 |
| recall    | 0.764199 |    0.507583 |
| mcc       | 0.628366 |    0.507583 |


## Confusion matrix (at threshold=0.507583)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3633 |              594 |
| Labeled as 1 |              793 |             2570 |

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
