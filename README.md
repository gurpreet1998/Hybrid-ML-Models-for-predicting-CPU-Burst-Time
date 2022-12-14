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


Results: 

![R2](https://user-images.githubusercontent.com/37729999/207476826-10d65ce2-8f31-48ae-8f92-27f582aa77ec.png)
![Skew1](https://user-images.githubusercontent.com/37729999/207476832-3f5a91db-4b27-4918-b67a-6e6cac2425e6.png)
![skew2](https://user-images.githubusercontent.com/37729999/207476834-8949a717-411c-424e-b77e-c16632cd9abe.png)
![Table 1](https://user-images.githubusercontent.com/37729999/207476836-2dc5f1bb-59e4-4609-8212-30b3d9c74384.png)
![Table 2](https://user-images.githubusercontent.com/37729999/207476837-f52e7e53-7610-4550-8c16-dfc23e953697.png)
![R1](https://user-images.githubusercontent.com/37729999/207476838-b94474f6-8f53-42ea-b76f-d6487946d5d8.png)
