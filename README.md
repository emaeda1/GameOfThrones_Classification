# Predicting Deaths of Game Of Thrones Characters

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Data
Data Dictionary [data dictionary](https://github.com/emaeda1/GameOfThrones_Classification/blob/main/_data/GOT_data_dictionary.xlsx)

## Feature Engineering 
Gender 

## Models 
Different Models that I assessed:
Logistic
Random Forest
GBM (Gradient Boosting Machines)


## Results

Model           Train Accuracy   Test Accuracy       AUC Score      TN,  FP, FN,  TP
-----           --------------   -------------       ---------      ----------------
Logistic        0.7573           0.7538              0.5331         (4, 46, 2, 143)
Random Forest   0.9971           0.7795              0.629          (16, 34, 9, 136)
Tuned RF        0.791            0.8103              0.63           (13, 37, 0, 145)
GBM             0.8304           0.8103              0.6562         (17, 33, 4, 141)
Tuned GBM       0.8098           0.8359              0.6931         (20, 30, 2, 143)   

Tuned GBM is the best model with an AUC of 0.6931 
