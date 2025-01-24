# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                       |   Weight |
|:----------------------------|---------:|
| 10_Xgboost_SelectedFeatures |        1 |
| 11_Xgboost_SelectedFeatures |        1 |
| 3_Xgboost_SelectedFeatures  |        3 |
| 6_Xgboost_SelectedFeatures  |        6 |
| 7_Xgboost_SelectedFeatures  |        1 |

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.392286 | nan           |
| auc       | 0.911427 | nan           |
| f1        | 0.825388 |   0.368852    |
| accuracy  | 0.834924 |   0.449852    |
| precision | 0.988042 |   0.989164    |
| recall    | 1        |   4.24534e-05 |
| mcc       | 0.667997 |   0.449852    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.392286 |  nan        |
| auc       | 0.911427 |  nan        |
| f1        | 0.821578 |    0.449852 |
| accuracy  | 0.834924 |    0.449852 |
| precision | 0.81975  |    0.449852 |
| recall    | 0.823414 |    0.449852 |
| mcc       | 0.667997 |    0.449852 |


## Confusion matrix (at threshold=0.449852)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3527 |              648 |
| Labeled as 1 |              632 |             2947 |

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
