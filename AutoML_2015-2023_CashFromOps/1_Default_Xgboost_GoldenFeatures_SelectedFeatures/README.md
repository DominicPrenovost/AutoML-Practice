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

73.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.485997 | nan           |
| auc       | 0.865418 | nan           |
| f1        | 0.78566  |   0.345002    |
| accuracy  | 0.79139  |   0.518835    |
| precision | 0.971519 |   0.992028    |
| recall    | 1        |   8.44197e-05 |
| mcc       | 0.582359 |   0.518835    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.485997 |  nan        |
| auc       | 0.865418 |  nan        |
| f1        | 0.780695 |    0.518835 |
| accuracy  | 0.79139  |    0.518835 |
| precision | 0.796596 |    0.518835 |
| recall    | 0.765416 |    0.518835 |
| mcc       | 0.582359 |    0.518835 |


## Confusion matrix (at threshold=0.518835)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3230 |              729 |
| Labeled as 1 |              875 |             2855 |

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
