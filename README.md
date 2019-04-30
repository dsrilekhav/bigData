# Description
Using Spark to query Analytical questions on the [MovieLens dataset](https://grouplens.org/datasets/movielens/1m/) containing a million records using Spark. This features the use of Spark RDD, Spark SQL and Spark Dataframes executed on Spark-Shell using Scala API.

## Environment
* Linux (Ubuntu 15.04)
* Hadoop 2.7.2
* Spark 2.0.2

## Analysis that can be drawn through this script

### Spark RDD
1. What are the top 10 most viewed movies?
2. What are the distinct list of genres available?
3. How many movies for each genre?
4. How many movies are starting with numbers or letters (Example: Starting with 1/2/3../A/B/C..Z)?
5. List the latest released movies

### Spark SQL
1. Find the list of the oldest released movies.
2. Create tables for movies.dat, users.dat and ratings.dat
3. How many movies are released each year?
4. How many number of movies are there for each rating?
5. For each movie,
   1. How many users rated? 
   2. What is the total rating? 
   3. What is the average rating?

### Spark DataFrames
1. Clean data and convert into Dataframe
