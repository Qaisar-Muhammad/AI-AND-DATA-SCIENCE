# Naive Bayes Classifiers Lab

## Objective

The objective of this lab was to implement and compare different Naive Bayes classifiers on the Iris dataset and perform prediction using user-provided flower measurements.

---

## Models Used

- Gaussian Naive Bayes
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Complement Naive Bayes

---

## Performance Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Observations

### GaussianNB

- Best suited for continuous numerical features.
- Usually gives the highest accuracy on the Iris dataset.

### MultinomialNB

- Designed for count-based data.
- Works after scaling data to positive values.

### BernoulliNB

- Requires binary features.
- Information loss occurs during binarization.

### ComplementNB

- Variant of MultinomialNB.
- Useful for imbalanced datasets.

---

## Best Performing Model

For the Iris dataset, **Gaussian Naive Bayes** generally performs best because all features are continuous measurements.

---

## Effect of Data Type

- Continuous data → GaussianNB performs better
- Count data → MultinomialNB performs better
- Binary data → BernoulliNB performs better

---

## Impact of Binarization

Converting continuous values to binary values may reduce information, which can lower accuracy and F1-score.

---

## Conclusion

Gaussian Naive Bayes achieved the best performance on the Iris dataset because the dataset contains continuous numerical features. BernoulliNB generally showed lower performance due to binarization, while MultinomialNB and ComplementNB produced moderate results after scaling the data.
