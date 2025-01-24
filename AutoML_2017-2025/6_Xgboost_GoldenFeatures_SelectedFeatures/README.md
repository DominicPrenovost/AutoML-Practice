# Summary of 6_Xgboost_GoldenFeatures_SelectedFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.05
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

60.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.404674 | nan           |
| auc       | 0.903277 | nan           |
| f1        | 0.810377 |   0.381344    |
| accuracy  | 0.831225 |   0.513718    |
| precision | 0.987805 |   0.995199    |
| recall    | 1        |   6.67948e-06 |
| mcc       | 0.656971 |   0.442219    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.404674 |  nan        |
| auc       | 0.903277 |  nan        |
| f1        | 0.803738 |    0.513718 |
| accuracy  | 0.831225 |    0.513718 |
| precision | 0.829014 |    0.513718 |
| recall    | 0.779958 |    0.513718 |
| mcc       | 0.656877 |    0.513718 |


## Confusion matrix (at threshold=0.513718)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3686 |              541 |
| Labeled as 1 |              740 |             2623 |

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
