# Anomaly_Detection_with_PCA
This repo hosts an Unsupervised Machine Learning [model](https://github.com/arashshams/Anomaly_Detection_with_PCA/blob/master/Analysis.ipynb) for [Anomaly Detection](https://en.wikipedia.org/wiki/Anomaly_detection) using [PCA](https://medium.com/apprentice-journal/pca-application-in-machine-learning-4827c07a61db) (Principal Component Analysis) on [Kaggle's Credit Card Fraud Detection data set](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The dataset contains transactions made by credit cards in September 2013 by European cardholders.

**Note:** The data set is not included in this repo due to size limitations. Make sure to download the data (`creditcard.csv`) from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and put it in the project root.

### Dependencies

If you want to reproduce the [report](https://github.com/arashshams/Anomaly_Detection_with_PCA/blob/master/Analysis.ipynb) (`Analysis.ipynb`) on your local, simply run below commands in terminal to create the environment for running the notebook.

```
conda env create -f environment.yml
conda activate env
```
