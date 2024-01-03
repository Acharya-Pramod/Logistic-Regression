Logistic Regression: Logistic Regression is a statistical model used for binary classification tasks. It predicts the probability that an instance belongs to a particular class, applying a logistic 
function to a linear combination of input features. It's widely used due to its simplicity and effectiveness in predicting probabilities.


Summary: 
1. Utilized `GridSearchCV` to systematically explore and find the best hyperparameter (`C`) for a Logistic Regression model through cross-validation on the training set.
2. Trained the best model using the identified `C` on the entire training data.
3. Evaluated the model's performance on unseen data by calculating accuracy on the separate test set, providing insights into how well the model generalizes to new instances.
4. Used `predict_proba()` to obtain class probabilities for the test set, allowing for analysis beyond simple class predictions.
