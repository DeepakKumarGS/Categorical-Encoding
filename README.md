# Categorical-Encoding
Repository for Categorical Feature Encoding Challenge in Kaggle 2019 

Achieved rank of 687 out of 1342 participants 

### Techniques tried out : 

One hot encoding ( OHE) columns bin_0 to bin_4

Frequency encoding colums with high cardinality - nom_0 to nom_9 , ord_0 to ord_5,day,month 

### Model

LGBM with 5 fold cross validation .Parameters optimized through bayesian optimization 

### Techniques which did not work 

1.Feature engineering - Split ord_5 into two columns and frequency encode

2.Remove variables which are present in 0.1% of the total data for columns with high cardinality


