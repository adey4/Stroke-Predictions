# Stroke-Predictions
Use clinical patient information to predict strokes

# Final Model:
XGBClassifier with eta = 0.3, lambda = 0, max_depth = 9, and min_child_weight = 1

# Model Evaluation
The final model was chosen to maximize recall, since false negatives are worse than false positives when predicting stroke. The final model had a recall of 0.09, with an accuracy of 0.93 that was very close to the other tested models. 
