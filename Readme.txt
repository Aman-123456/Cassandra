'Question 5 python code and Schema explain below : '

Question 5 Schema, hashtag is made Partition key beacuse data should be partitioned by hashtags and this hashtag will used in 'where' Clause of query . And for cluster key, I used count beacuse we have to sort the tuples in decresing order of count and for uniqueness of the row, used date also.

In python code - first i connected with cassandra server.
then I made a keyspace whose name is "test4"
then I used table with name "mytable"
then  glob.glob used to get all files from dataset.

then I inserted only those Hashtags which is required in table then used dictionary which count the hashtags.


'Question 11 python code and Schema explain below : '

Question 11 Schema, date is made Partition key beacuse this date will used in 'where' Clause of the query . And for cluster key, I used count beacuse we have to sort the tuples in decresing order of count.

In python code - first i connected with cassandra server.
then I made a keyspace whose name is "test4"
then I used table with name is "mytable"
then  glob.glob used to get all files from dataset.

then I made dictionary whose key is string (mention+location) and value is frequency of this .
 