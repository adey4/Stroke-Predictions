# Stroke-Predictions
Use clinical patient information to predict strokes

# Final Model
XGBClassifier with eta = 0.3, lambda = 1, max_depth = 5, and min_child_weight = 2

# Model Evaluation
The final model was chosen to maximize recall, since false negatives are worse than false positives when predicting stroke. False negatives may lead to a lack of proper treatment for those who might be at risk for stroke, while false positives only lead to an unnecessary checkup.

The final model showed a recall of 0.07, with an accuracy of 0.94 that was very close to the other tested models. The model also showed a precision of 0.40 and an f1-score of 0.13.

# Recommendations
Further research and model development is required to obtain a suitable model for production use. The final model's recall of 0.07 is still low for stroke predictions, and may lead to dangerous false negative errors.
