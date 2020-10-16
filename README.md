# Dimensionality Reduction 

The aim of this project was to examine differ ways to reduce dimensionality in high dimension sets, in this case the MNIST handwritten digit database. Dimensionality reduction is implemented to lessen the sets complexity without losing variance. This allows faster model training and the ability to visualise clusters. This project used both principal component analysis (PCA) and t-distributed stochastic neighbour (TSNE) embedding. To visualisations were made in 2D and 3D and models were compared on the original and reduce data sets.

| Model                   | Xgboost  |   | SVC      |   | Random Forest |   | KNeighbors |   | Average  |
|-------------------------|----------|---|----------|---|---------------|---|------------|---|----------|
| Time Reduction          | 92.43159 |   | 91.86185 |   | 79.45173      |   | 92.51669   |   | 89.06547 |
| Loss / Gain in Accuracy | -1.06829 |   | 13.48592 |   | -2.66517      |   | 0.620664   |   | 2.59328  |

Models improved in speed by an average of 89.07% and interesting overall the model maintained roughly the same level of accuracy, ranging from 2.67% less to 13.49% more.
