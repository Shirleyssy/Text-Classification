Here, 5 feature selection methods (TFIDF, information gain (ig), mutual Information (mi), log likelihood ratio (llr) and chi-squared stats (chi2)) has been tested with different size of features subsets, from 1000 to 5000.

In the experiment, stem-tokenizers is used to turns the input into a character vector of word stems. And stopword is downloaded from nltk. After getting the initial features set, using feature selection method get the features subsets. Then, based on this feature subset, using Naive-Bayes-Text-Classification model train the classifier and using k fold cross validation (k=6) validate the result.

to run this ipynb file, test.csv and train.csv need to be uploaded in the same folder with this ipynb file. Then run all, the result for different size of features subsets will print.

note: you must run again to reload the result, as the current result is from a small dataset for debug.