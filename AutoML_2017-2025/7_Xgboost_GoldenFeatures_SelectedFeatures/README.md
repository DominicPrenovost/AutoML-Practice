# Summary of 7_Xgboost_GoldenFeatures_SelectedFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
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

36.5 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.403002 | nan          |
| auc       | 0.905659 | nan          |
| f1        | 0.812384 |   0.369      |
| accuracy  | 0.835441 |   0.576392   |
| precision | 0.987147 |   0.990769   |
| recall    | 1        |   2.2291e-06 |
| mcc       | 0.665947 |   0.576392   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.403002 |  nan        |
| auc       | 0.905659 |  nan        |
| f1        | 0.80414  |    0.576392 |
| accuracy  | 0.835441 |    0.576392 |
| precision | 0.850697 |    0.576392 |
| recall    | 0.762415 |    0.576392 |
| mcc       | 0.665947 |    0.576392 |


## Confusion matrix (at threshold=0.576392)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3777 |              450 |
| Labeled as 1 |              799 |             2564 |

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
