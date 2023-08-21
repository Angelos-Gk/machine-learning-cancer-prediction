# machine-learning-cancer-prediction
A python script to predict cancer type based on gene expression values using a machine learning model (Random Forest classifier).
Data avalailable at: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq)
First, we download and import the data, then we perform some cleaning and formatting. Afterwards, the preprocessing takes place, where we separate values from class, encode the labels, split the data into training and test subsets and finally normalize the data. In the end, we select the top features and train the model, and finally we evaluate the model using many different metrics (accuracy, precision, recall, f1 score, confusion matrix, ROC Curve).
