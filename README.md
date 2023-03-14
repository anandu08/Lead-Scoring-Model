# Lead Scoring Model
This project uses machine learning to predict lead scores for potential customers. The lead score ranges from 0-100 and represents the likelihood of a lead being converted into a booking.

**#Data**
The model is trained on a dataset of leads with their set of features and status. The leads with status other than ‘WON’ or ‘LOST’ are dropped during training. All columns are treated as categorical columns.


**#Methodology**
The project follows these steps:

Data Cleaning (including Feature Selection)
Training (on Y percent of data)
Testing (on (100-Y) percent of data)
Evaluate the performance using metrics such as accuracy, precision, recall, and F1-score.

**#Results**

   precision    recall  f1-score   support

         0.0       0.93      1.00      0.96     12927
         1.0       0.00      0.00      0.00       969

    accuracy                           0.93     13896
   macro avg       0.47      0.50      0.48     13896
weighted avg       0.87      0.93      0.90     13896
