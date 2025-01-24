# Summary of 8_Xgboost_GoldenFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
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

131.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.500091 | nan           |
| auc       | 0.86121  | nan           |
| f1        | 0.779568 |   0.402995    |
| accuracy  | 0.785668 |   0.486218    |
| precision | 0.979167 |   0.994742    |
| recall    | 1        |   9.20193e-05 |
| mcc       | 0.570817 |   0.486218    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.500091 |  nan        |
| auc       | 0.86121  |  nan        |
| f1        | 0.776996 |    0.486218 |
| accuracy  | 0.785668 |    0.486218 |
| precision | 0.784426 |    0.486218 |
| recall    | 0.769705 |    0.486218 |
| mcc       | 0.570817 |    0.486218 |


## Confusion matrix (at threshold=0.486218)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3170 |              789 |
| Labeled as 1 |              859 |             2871 |

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
