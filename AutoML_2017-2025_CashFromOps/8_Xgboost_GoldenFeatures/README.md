# Summary of 8_Xgboost_GoldenFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.05
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

311.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.481226 | nan           |
| auc       | 0.869744 | nan           |
| f1        | 0.784995 |   0.344967    |
| accuracy  | 0.787747 |   0.363412    |
| precision | 1        |   0.992248    |
| recall    | 1        |   8.24647e-05 |
| mcc       | 0.57892  |   0.363412    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.481226 |  nan        |
| auc       | 0.869744 |  nan        |
| f1        | 0.784308 |    0.363412 |
| accuracy  | 0.787747 |    0.363412 |
| precision | 0.748339 |    0.363412 |
| recall    | 0.82391  |    0.363412 |
| mcc       | 0.57892  |    0.363412 |


## Confusion matrix (at threshold=0.363412)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3050 |              985 |
| Labeled as 1 |              626 |             2929 |

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
