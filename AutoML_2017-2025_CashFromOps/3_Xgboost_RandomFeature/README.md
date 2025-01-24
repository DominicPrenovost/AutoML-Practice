# Summary of 3_Xgboost_RandomFeature

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
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

597.4 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.50679  | nan           |
| auc       | 0.868933 | nan           |
| f1        | 0.785405 |   0.300696    |
| accuracy  | 0.788933 |   0.41904     |
| precision | 1        |   0.996955    |
| recall    | 1        |   2.38492e-05 |
| mcc       | 0.57748  |   0.41904     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.50679  |   nan       |
| auc       | 0.868933 |   nan       |
| f1        | 0.778851 |     0.41904 |
| accuracy  | 0.788933 |     0.41904 |
| precision | 0.764706 |     0.41904 |
| recall    | 0.79353  |     0.41904 |
| mcc       | 0.57748  |     0.41904 |


## Confusion matrix (at threshold=0.41904)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3167 |              868 |
| Labeled as 1 |              734 |             2821 |

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
