# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                                             |   Weight |
|:--------------------------------------------------|---------:|
| 10_Xgboost_GoldenFeatures_SelectedFeatures        |        1 |
| 1_Default_Xgboost_GoldenFeatures_SelectedFeatures |        1 |
| 3_Xgboost_GoldenFeatures                          |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.471763 | nan          |
| auc       | 0.869367 | nan          |
| f1        | 0.790746 |   0.406391   |
| accuracy  | 0.794772 |   0.491096   |
| precision | 0.987805 |   0.994889   |
| recall    | 1        |   0.00010542 |
| mcc       | 0.589054 |   0.491096   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.471763 |  nan        |
| auc       | 0.869367 |  nan        |
| f1        | 0.786468 |    0.491096 |
| accuracy  | 0.794772 |    0.491096 |
| precision | 0.793989 |    0.491096 |
| recall    | 0.779088 |    0.491096 |
| mcc       | 0.589054 |    0.491096 |


## Confusion matrix (at threshold=0.491096)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3205 |              754 |
| Labeled as 1 |              824 |             2906 |

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
