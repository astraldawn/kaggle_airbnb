##Data##
- Users
 - Look at the Kaggle script to gain more insight to the dataset
- Sessions
 - More than 1 million rows of session data 

##Feature generation##
 - Sessions
  - Number of sessions
  - Average duration of each session
  - Stuff that they looked at during each session, maybe come up with a ranking
 - Feature selection
  - PCA
  - KMeans
  - Other more advanced feature selection methods? See what scikit provides

##Techniques##
- XGBOOST
 - Looks as though the parameters have been tweaked
- Clustering
 - Should be able to generate clusters quickly. Then run XGBOOST within cluster. [Potential overfitting]

##Useful links##
- http://nerds.airbnb.com/overcoming-missing-values-in-a-rfc/
- http://nbviewer.jupyter.org/github/lmcinnes/hdbscan/blob/master/notebooks/Benchmarking%20scalability%20of%20clustering%20implementations-v0.6.ipynb
- http://nbviewer.jupyter.org/github/lmcinnes/hdbscan/blob/master/notebooks/Comparing%20Clustering%20Algorithms.ipynb (HDBSCAN clustering algorithm)
