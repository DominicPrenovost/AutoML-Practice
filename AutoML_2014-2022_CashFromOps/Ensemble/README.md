# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                    |   Weight |
|:-------------------------|---------:|
| 3_Xgboost                |        1 |
| 3_Xgboost_GoldenFeatures |        1 |
| 6_Xgboost_GoldenFeatures |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.447405 | nan          |
| auc       | 0.884586 | nan          |
| f1        | 0.794797 |   0.386153   |
| accuracy  | 0.805262 |   0.51513    |
| precision | 1        |   0.996327   |
| recall    | 1        |   1.7893e-05 |
| mcc       | 0.608466 |   0.51513    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.447405 |   nan       |
| auc       | 0.884586 |   nan       |
| f1        | 0.786482 |     0.51513 |
| accuracy  | 0.805262 |     0.51513 |
| precision | 0.808195 |     0.51513 |
| recall    | 0.765905 |     0.51513 |
| mcc       | 0.608466 |     0.51513 |


## Confusion matrix (at threshold=0.51513)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3463 |              660 |
| Labeled as 1 |              850 |             2781 |

## Learning curves
![Learning curves](learning_curves.png)
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
