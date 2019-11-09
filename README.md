# Youtube-Comment-Analysis

Go to the following link:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2594974024605020/1791629972216163/6812779388620103/latest.html

	Analyzed the comment data under animal or pet channel, and tried to identify if the user is a dog or a cat owner.

	Applied Spark Dataframe to do data ETL and made N-gram analysis to build regex to label the unlabeled data. 

	Utilized Spark ML to implemented Logistic Regression, Random Forest and Gradient Boosting Trees on vectors from Word2Vec to classify the data and attained AUC of 96.11% in GBT.

	Implemented LDA to model topics for comments after Tf-idf to find out dog/cat owners’ interests, and made recommendation on who to give ads to and where to place the ads.
