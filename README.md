# SparkRecommenderSystem

### Movie Recommendations on Spark with Scala

Recommender systems are becoming a key tool for client-oriented companies.  
I tried my hand at it for some movie recommendations.

![](https://raw.githubusercontent.com/Hugo-Nattagh/SparkRecommenderSystem/master/resources/12.png)

#### What's going on

To process a large volume of data, I chose Spark.
I used the [MovieLens](https://grouplens.org/datasets/movielens/100k/) dataset.

I played around with dataframes and RDDs to display the ratings of an user.  
His missing ratings were then predicted by the [ALS](https://github.com/databricks/spark-training/blob/master/website/movie-recommendation-with-mllib.md) algorithm, from the [mllib](https://spark.apache.org/mllib/) library of Spark.  
I then displayed the top 7 recommendations for this user.

I had the idea from [Frank Kane](https://www.youtube.com/watch?v=I2L_J4l6YbY&list=PL6cactdCCnTJ2XZYIQYIwLperpbKB86jv&index=8&t=0s), although he used PySpark.
