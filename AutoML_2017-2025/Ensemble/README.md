# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                                             |   Weight |
|:--------------------------------------------------|---------:|
| 10_Xgboost_GoldenFeatures_SelectedFeatures        |        1 |
| 11_Xgboost_GoldenFeatures_SelectedFeatures        |        5 |
| 1_Default_Xgboost_GoldenFeatures_SelectedFeatures |        2 |
| 3_Xgboost                                         |        1 |
| 7_Xgboost_GoldenFeatures_SelectedFeatures         |        3 |

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.390514 | nan           |
| auc       | 0.910061 | nan           |
| f1        | 0.818808 |   0.415856    |
| accuracy  | 0.837945 |   0.489871    |
| precision | 0.993902 |   0.995613    |
| recall    | 1        |   5.20535e-06 |
| mcc       | 0.671019 |   0.415856    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.390514 |  nan        |
| auc       | 0.910061 |  nan        |
| f1        | 0.813693 |    0.489871 |
| accuracy  | 0.837945 |    0.489871 |
| precision | 0.829268 |    0.489871 |
| recall    | 0.798692 |    0.489871 |
| mcc       | 0.670763 |    0.489871 |


## Confusion matrix (at threshold=0.489871)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3674 |              553 |
| Labeled as 1 |              677 |             2686 |

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
