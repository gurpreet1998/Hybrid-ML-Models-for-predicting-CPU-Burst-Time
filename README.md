# Hybrid-ML-Models-for-predicting-CPU-Burst-Time

Utilizing CPU optimally is pertinent for making the processes execution look parallel. Some of the CPU scheduling algorithms like Shortest-Remaining-Time-First (SRTF) and Shortest-Job-First (SJF) need CPU burst time, beforehand so that the processes in the wait queue can be scheduled in an
optimal way. There are various existing mathematical techniques to find out the burst time of the process but they are proved
to be expensive. This paper proposed several hybrid prediction
machine learning models and feature selection techniques are
used. ML model includes Linear Regressor, Ridge Regression,
Lasso, Random Forest (RF) Regressor, Support Vector Regressor
(SVR), K-Nearest Neighbor (KNN) and Decision-Tree Regressor
(DT) have been used. Models have been trained using GWAT-4 AuverGrid dataset provided by TuDelft. Mean Absolute
Error and R2 Score are used to evaluate the trained algorithm’s
performance. On testing data, the Decision-Tree and Random
Forest outperformed every other regression algorithm which
achieves an R2 of 0.90, while K-nearest, SVR, and Linear Regression achieve 0.8754, 0.8045, and 0.7926, respectively. Empirical
evidence demonstrates the sup
