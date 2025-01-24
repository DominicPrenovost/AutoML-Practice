# Summary of 1_Default_Xgboost_GoldenFeatures_SelectedFeatures

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

49.5 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.4078   | nan           |
| auc       | 0.906444 | nan           |
| f1        | 0.81611  |   0.369687    |
| accuracy  | 0.832938 |   0.445382    |
| precision | 0.987805 |   0.996732    |
| recall    | 1        |   3.36105e-06 |
| mcc       | 0.661889 |   0.393255    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.4078   |  nan        |
| auc       | 0.906444 |  nan        |
| f1        | 0.812204 |    0.445382 |
| accuracy  | 0.832938 |    0.445382 |
| precision | 0.809088 |    0.445382 |
| recall    | 0.815343 |    0.445382 |
| mcc       | 0.661773 |    0.445382 |


## Confusion matrix (at threshold=0.445382)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3580 |              647 |
| Labeled as 1 |              621 |             2742 |

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
