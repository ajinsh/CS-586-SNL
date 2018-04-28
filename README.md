# CS-586-SNL
SNL Data Analysis

Highlights :- Data cleaning csv file from Kaggle, splitting csv file into multiple CSV files for Data Modeling purpose. Run DDL commands for table 
creation using CSV file as data source in PostgreSQL.

## Data Wrangling Stage

- Data Cleaned up by splitting the [source csv file](https://www.kaggle.com/hhllcks/snldb/data) into normalized csv files
```
Note: Normalized CSV files are created using ER Modeling Rules

```

## Data Loading Stage

- Data Loading into PostgreSQL using Import Functionality by writing [SQL scripts](schema_script.sql)

## Analysis of SNL DataSet

Find interesting insights for the dataset loaded such as 

- Which actor played in most sketches?
- Which are the actors who appeared in atleast 2 episodes?
- Which are the actors who performed the longest in all the seasons?
- Which season has most number of ratings?
- For how much duration of a given season the actor appeared?
- Give the episode information which run for the longest time.
- Top 3 cast members who are still working in the show.
- Which episode had huge ratings ?
- Which are the episodes in which _Coldplay_ artist performed ?
- List cast members who have atleast 20 episodes.
- Top 10 actors of SNL
- Worst 10 actors of SNL
- What are the average ratings per season?
- Give the list of top 3 impressions performed.
- List 10 characters played by the actor _Kristen Wig_.
- What is the tenure of an actor on the show ?
- List all musical performance for the season no. 28.
- Which episodes show advertisement of "HBO First Look".
- List the synopsis of a given epsiode.
- What is the first, last episode aired date for all seasons so far?
