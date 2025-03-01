Summary:
Tried using multiple deep learning models on raw UCI HAR dataset.
Classification results using the 2D CNN models:
Accuracy: 0.9301
Recall: 0.9301
Precision: 0.9302
F1-score: 0.9300

Classification Report:
              precision    recall  f1-score   support

           0       0.95      0.95      0.95       496
           1       0.97      0.93      0.95       471
           2       0.92      0.97      0.94       420
           3       0.87      0.86      0.86       491
           4       0.88      0.87      0.87       532
           5       1.00      1.00      1.00       537

    accuracy                           0.93      2947
   macro avg       0.93      0.93      0.93      2947
weighted avg       0.93      0.93      0.93      2947


Confusion Matrix:
[[473   0  23   0   0   0]
 [ 21 439  11   0   0   0]
 [  4  10 406   0   0   0]
 [  1   3   0 421  66   0]
 [  0   2   0  65 465   0]
 [  0   0   0   0   0 537]]

 Classification results using 2D-CNN-LSTM-Transformer model:
Accuracy: 0.9430
Recall: 0.9430
Precision: 0.9431
F1-score: 0.9429

Classification Report:
              precision    recall  f1-score   support

           0       0.98      0.97      0.98       496
           1       0.98      0.97      0.97       471
           2       0.96      0.98      0.97       420
           3       0.88      0.84      0.86       491
           4       0.86      0.89      0.88       532
           5       1.00      1.00      1.00       537

    accuracy                           0.94      2947
   macro avg       0.94      0.94      0.94      2947
weighted avg       0.94      0.94      0.94      2947


Confusion Matrix:
[[482   1  13   0   0   0]
 [  7 458   6   0   0   0]
 [  1   7 412   0   0   0]
 [  0   2   0 414  75   0]
 [  0   1   0  55 476   0]
 [  0   0   0   0   0 537]]

Using of expert-engineered data gave just slight improvement but not much
