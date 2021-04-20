# tabular-data-methods

CSC413 Final Course Project - exploring deep learning methods for tabular datasets

This experiment tests out two novel deep learning techniques for tabular data - TabNet and NODE (Neural Oblivious Decision Ensembles) and compares them to XGBoost (extreme gradient boosting decision trees). The test is performed over two tabular datasets of different natures, the Adult Income dataset (classification task), and the Rossmann Stores dataset (regression task).

The `data` folder contains the datasets in csv format. The `experiment_notebooks` folder contains 4 ipython notebooks consisting our experiments, as well as the code implementations of TabNet (`pytorch_tabnet`) and NODE (`node`).