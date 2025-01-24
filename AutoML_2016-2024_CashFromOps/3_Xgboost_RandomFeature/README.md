# Summary of 3_Xgboost_RandomFeature

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
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

101.7 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.507102 | nan           |
| auc       | 0.858779 | nan           |
| f1        | 0.779898 |   0.316308    |
| accuracy  | 0.779845 |   0.490959    |
| precision | 0.981132 |   0.997402    |
| recall    | 1        |   0.000272298 |
| mcc       | 0.560881 |   0.397647    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.507102 |  nan        |
| auc       | 0.858779 |  nan        |
| f1        | 0.76834  |    0.490959 |
| accuracy  | 0.779845 |    0.490959 |
| precision | 0.773459 |    0.490959 |
| recall    | 0.763288 |    0.490959 |
| mcc       | 0.558664 |    0.490959 |


## Confusion matrix (at threshold=0.490959)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3165 |              816 |
| Labeled as 1 |              864 |             2786 |

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
