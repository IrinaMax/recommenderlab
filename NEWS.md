# Changes in version 0.1-9.1 (xx/xx/2016)

* Added getRatings method for topNList.
* realRatingMatrix supports now subset assignment with [.
* RECOM_POPULAR now shows the parameters in the registry. 
* predict now checks if newdata (number of items) is compatible with the model.  

# Changes in version 0.1-9 (05/18/2016)

* FIX: rownames of newdata are now preserved in prediction output.
* we use testthat now.
* normalization now can be done on rows and columns at the same time.
* SVD with column-mean imputation now folds in new users.
* added Funk SVD (funkSVD and recommender SVDF).
* added function error measures: MAE, MSE, RMSE, frobenius (norm).
* Jester5k contains now the jokes.
* MovieLense contains now movie meta information.
* topNLists now also contains ratings.
* removed obsolete PCA-based recommender.

# Changes in version 0.1-8 (12/17/2015)

* fixed several problems in the vignette.
* predict for realRatingMatrix accepts now type = "ratingMatrix" to returns
  a completed rating matrix.
* Negative values for given in evaluationScheme implement all-but-given 
  evaluation.
* method "SVD" used now EM-based approximation from package bcv.

# Changes in version 0.1-7 (7/23/2015)

* NAMESPACE now imports non standard R packages.

# Changes in version 0.1-5 (8/18/2014)

* Fixed NAMESPACE problems.
* evaluation of ratings is now better integrated into evaluate.
* binarize keeps now dimnames.

# Changes prior to 0.1-4 (1/11/2013)

* many

# Alpha version 0.1-0 (1/23/2010)
