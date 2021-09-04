# cat-in_the_dat_ii
Binary classification, with every feature a categorical (and interactions!)

### DESCRIPTION
Can you find more cat in your dat?

This competition offers a even more challenging dataset, compared to the cat in the dat-i , so that you can continue to build your skills with the common machine learning task of encoding categorical variables. This challenge adds the additional complexity of feature interactions, as well as missing data.

### DATA DESCRIPTION
In this competition, you will be predicting the probability [0, 1] of a binary target column.

The data contains binary features (bin_*), nominal features (nom_*), ordinal features (ord_*) as well as (potentially cyclical) day (of the week) and month features. The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.

Since the purpose of this competition is to explore various encoding strategies. Unlike the first Categorical Feature Encoding Challenge, the data for this challenge has missing values and feature interactions.

### EVALUATION:
Evaluated on area under the ROC curve between the predicted probability and the observed target.
