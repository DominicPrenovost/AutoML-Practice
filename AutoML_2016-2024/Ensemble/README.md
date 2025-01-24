# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                    |   Weight |
|:-------------------------|---------:|
| 3_Xgboost                |        1 |
| 3_Xgboost_GoldenFeatures |        1 |
| 6_Xgboost_GoldenFeatures |        1 |

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.425743 | nan           |
| auc       | 0.893027 | nan           |
| f1        | 0.809016 |   0.365832    |
| accuracy  | 0.817324 |   0.428992    |
| precision | 1        |   0.996683    |
| recall    | 1        |   7.17524e-05 |
| mcc       | 0.634037 |   0.428992    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.425743 |  nan        |
| auc       | 0.893027 |  nan        |
| f1        | 0.808253 |    0.428992 |
| accuracy  | 0.817324 |    0.428992 |
| precision | 0.798804 |    0.428992 |
| recall    | 0.817929 |    0.428992 |
| mcc       | 0.634037 |    0.428992 |


## Confusion matrix (at threshold=0.428992)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3299 |              740 |
| Labeled as 1 |              654 |             2938 |

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
