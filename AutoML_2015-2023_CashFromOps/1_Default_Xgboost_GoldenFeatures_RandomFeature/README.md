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

112.3 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.49359  | nan           |
| auc       | 0.857964 | nan           |
| f1        | 0.777749 |   0.419421    |
| accuracy  | 0.784888 |   0.537921    |
| precision | 0.974684 |   0.990519    |
| recall    | 1        |   0.000104711 |
| mcc       | 0.569606 |   0.537921    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.49359  |  nan        |
| auc       | 0.857964 |  nan        |
| f1        | 0.771484 |    0.537921 |
| accuracy  | 0.784888 |    0.537921 |
| precision | 0.795895 |    0.537921 |
| recall    | 0.748525 |    0.537921 |
| mcc       | 0.569606 |    0.537921 |


## Confusion matrix (at threshold=0.537921)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3243 |              716 |
| Labeled as 1 |              938 |             2792 |

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
