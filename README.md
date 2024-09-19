## Evaluation Metrics

### Precision
Precision measures the proportion of true positive predictions among the total positive predictions. It is given by:

\[ \text{Precision} = \frac{TP}{TP + FP} \]

where:
- \( TP \) = True Positives
- \( FP \) = False Positives

### Recall
Recall (or Sensitivity) measures the proportion of true positive predictions among the total actual positives. It is given by:

\[ \text{Recall} = \frac{TP}{TP + FN} \]

where:
- \( TP \) = True Positives
- \( FN \) = False Negatives

### F1 Score
The F1 Score is the harmonic mean of Precision and Recall. It balances both metrics, especially when you need to account for both false positives and false negatives. It is given by:

\[ \text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} \]

### Accuracy
Accuracy measures the proportion of correctly classified instances among the total instances. It is given by:

\[ \text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN} \]

where:
- \( TP \) = True Positives
- \( TN \) = True Negatives
- \( FP \) = False Positives
- \( FN \) = False Negatives
