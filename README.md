# sentiment_analysis-using-Pyspark

Twitter is a social media site and its primary purposes are to convert people and allow people to share their thoughts.

Twitter an American Microbe Using twitter social media users post their views, opinions and to communicate with messages called as tweets

Sentimental analysis means the analysis and classification of the emotions and feelings such as positive thought, negative

thought and neutral thought using text analysis techniques within text data.

The idea is to solve people’s dilemma for choosing a certain product or service over other. The objective is to collect data from tweeter feeds on trending topics

This Project would use Scala and Spark cluster. All the Big Data that would be fetched would be collected in MySQL database. 

The filter on this data is based on a list of keywords supplied. This analysis will employee a distributed data processing system known as Apache Spark using several 

worker and master nodes. This cluster is scalable and can handle millions of records.

 Spark SQL :
 
Spark core has an SQL extension which supports more optimization on datasets(RDD) and is in structured format to retrieve data using the SQL queries. Spark SQL 

provides

most convenient way to perform several transitions on the data. Spark SQL  uses dataframes for data manipulations. 

Streaming Twitter Data Using PySpark

We use spark streaming to stream live spark data. To load Twitter data into Apache Spark

twitter provides an interface to developers which can be used to access twitter data. Visit twitters applications site to register your application 

“https://apps.twitter.com/”. I

have noted twitter tokens into TwitterKeys.txt which are needed to initialize spark streaming context. The streaming data is captured into batches. 

We set the filter which contains set of keywords to filter the tweets. Only tweets with those keywords present in it would be streamed.

![image](https://user-images.githubusercontent.com/120237181/229187905-0ba36268-d7e0-4041-9ac7-420830fc8c94.png)

