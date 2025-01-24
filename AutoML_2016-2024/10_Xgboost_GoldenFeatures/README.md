# Summary of 10_Xgboost_GoldenFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
- **max_depth**: 8
- **min_child_weight**: 5
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

95.5 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.439087 | nan          |
| auc       | 0.882827 | nan          |
| f1        | 0.795088 |   0.366624   |
| accuracy  | 0.805792 |   0.496912   |
| precision | 0.990566 |   0.995179   |
| recall    | 1        |   6.1293e-06 |
| mcc       | 0.60982  |   0.496912   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.439087 |  nan        |
| auc       | 0.882827 |  nan        |
| f1        | 0.789548 |    0.496912 |
| accuracy  | 0.805792 |    0.496912 |
| precision | 0.805797 |    0.496912 |
| recall    | 0.773942 |    0.496912 |
| mcc       | 0.60982  |    0.496912 |


## Confusion matrix (at threshold=0.496912)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3369 |              670 |
| Labeled as 1 |              812 |             2780 |

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
