# databricks_projects
This is a repo containing links to all my databricks projects
# 1. Predicting Cat/Dog Owners from Youtube Comments
For this project, I achieved the following things:

· Trained a model to identify cat or dog owners from their YouTube comments. Obtained training data by filtering 6M comments heuristically, then manually labelling them based on statements such as ”I have a dog/cat”. Used Apache Spark and achieved 90% accuracy on held-out test data.

· Transformed text data to feature vectors using ML pipeline, RegexTokenizer and WordtoVec embeddings.

· Downsampled negative labels to overcome data imbalance problem, used random sampling to split train/test data.

· Gained basic insights of users by generating word cloud based on word frequency.

link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4650916726781052/1165219182445618/4837853235479612/latest.html

# 2. Movie Recommender System in Apache Spark
For this project, I acheived the following things:

· Developed an algorithm to recommend movies based on 100,000 rows of movies and ratings data.

· Performed data analysis using SQL and OLAP(Online Analytical Processing) techniques.

· Designed ALS(Alternative Least Squares) matrix factorization recommender model using collaborative filtering

  and deployed on the Spark RDD API. The final model had a RMSE of 0.88 on test data.
  
link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4650916726781052/1165219182445670/4837853235479612/latest.html
