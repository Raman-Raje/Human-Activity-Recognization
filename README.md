# Human-Activity-Recognization
This repositary belongs to Human Activity Recognization case study

Dataset is available at https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones

Case Study Flow:-
===================
1. For the given case study, we have provided with both processed data and raw data from sensors.
2. We used processed data that was already featurized to build various machine learning models.
3. Eda was done on subject to check the various activity performed by them. We have got almost same number of reading from all the subjects.
4. Also the distribution of activity for data was found to be balanced.
5. We have tried and tested various models out of which Linear SVC gave the highesr accuracy of 96.61% with loss of 3.39%
6. But, the task was to achieve accuracy of more than 91% using Deep Learning Models.
7. First started with two layer LSTM with dropout of 0.6 to 0.4
8. For two layer LSTM, we Found that best result was obtained in case of droput of 0.5. Decrease in dropout leaded to overfitting of model as expected due to rise in # hyperparameters.
9. Next, We checked with single layer LSTM(128) with dropout rate varying from 0.5 to 0.7
10. Best result was found in case of LSTM(128) wit dropout of 0.6. We got accuracy of 91.82%
11. Also checked with single Layer LSTM(64) with droput varying from 0.2 to 0.6.
12. In every case , we found that dicrease in dropout rate was leading to model overfitting which is as expected.
