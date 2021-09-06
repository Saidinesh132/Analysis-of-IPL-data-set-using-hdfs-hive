IPL Data Analysis :
 1.In this , project I took IPL dataset from Kaggle .
2.Using the GUI of Ambari I have uploaded the file into HDFS.
3.Then I wrote the file into a table which was created in hive.
4.After importing file into the table in hive I performed some queries through which I want to do the analysis.
5.I took the output of the queries and exported them into HDFS.
6.From HDFS I exported the output files into database system using Sqoop. 
Technologies Used : 
1.Hadoop
2.Hdfs
3.Yarn
4.MapReduce
5.Hive
6.Sqoop

Problem Statement :
 we are having the record of the whole Indian premier league . we need some insights from that. The insights are given below . Also, we want these insights data to be copied into our database. Our database is MySql. We will let u know our credentials  of our database if you are done with those insights
INSIGHTS : 
1.Total number of records in the dataset.
2.Teams ,  count(number of times they won the toss).
3.Teams ,  count(number of times they won the matches).
4.Count(number of times  umpire1 ‘Ananthapadmaabhan’  is favour for teams).
5.Number of matches held in each season.
6.Top 5 man of the match awardees in the season 2019.
7.Count of man of match awards of each individual in all seasons.
8.Maximum number of mom’s for every season.
9.Files with  data matches held on each venue.
10.Into our database we need a file containing the records of man of the match , number of times they got mom’s.
