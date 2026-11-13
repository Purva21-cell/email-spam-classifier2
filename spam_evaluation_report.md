# Email Spam Classifier - Evaluation Report

## 1. Project Overview

The project uses a Logistic Regression classifier with TF-IDF
feature extraction to identify spam and legitimate SMS messages.

## 2. Model Configuration

- Algorithm: Logistic Regression
- Feature extraction: TF-IDF
- Maximum TF-IDF features: 5000
- Test size: 20%
- Random state: 42

## 3. Evaluation Results

| Metric | Score |
|---|---:|
| Accuracy | 0.9641 |
| Precision | 1.0000 |
| Recall | 0.7315 |
| F1-Score | 0.8450 |
| ROC-AUC | 0.9854 |

## 4. Confusion Matrix

| Actual / Predicted | Ham | Spam |
|---|---:|---:|
| Ham | 966 | 0 |
| Spam | 40 | 109 |

## 5. Classification Report

```text
              precision    recall  f1-score   support

         Ham       0.96      1.00      0.98       966
        Spam       1.00      0.73      0.84       149

    accuracy                           0.96      1115
   macro avg       0.98      0.87      0.91      1115
weighted avg       0.97      0.96      0.96      1115

```

## 6. Analysis

The classifier was evaluated using accuracy, precision,
recall, F1-score, confusion matrix, and ROC-AUC.

Precision indicates the reliability of spam predictions.
Recall measures the ability to identify actual spam messages.
The F1-score balances precision and recall.

## 7. Possible Improvements

1. Experiment with different TF-IDF configurations.
2. Compare Logistic Regression with Multinomial Naive Bayes.
3. Apply hyperparameter tuning using cross-validation.
4. Handle class imbalance using appropriate techniques.
5. Test the model on new and unseen SMS messages.
6. Experiment with n-grams and feature selection.
7. Monitor false positives and false negatives.

## 8. Conclusion

The evaluation provides a quantitative assessment of the
trained spam classification model. The results can be used
to identify strengths and areas requiring improvement.
