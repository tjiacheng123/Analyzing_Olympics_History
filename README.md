# Analyzing 120 years of Olympics History using SQL.

A Tableau dashboard has been developed to visualize the statstics for each region. The dashboard can be found in this [link](https://public.tableau.com/app/profile/toon.jia.cheng/viz/Analyzing120yearsofOlympicsHistoryByYear_16517210192780/Dashboard2).

We will be utilizing a rich dataset on the 120 years of Olympics history. It has information on the atheletes that have ever taken part in each of the Olympic event and the medals that have been awarded to them. The Olympic event is held every 4 years. The winter and summer Olympic games had traditionally been held in the same year up till 1992 where they delayed the winter Olympics by 2 years. From 1992 onwards, the Olympics games are held every 2 years, alternating between summer and winter olympics.

Using sql, we will attempt to answer the following questions:

1. How many olympics games have been held?
2. List down all Olympics games held so far.
3. Mention the total no of nations who participated in each olympics game?
4. Which year saw the highest and lowest no of countries participating in olympics?
5. Which nation has participated in all of the olympic games?
6. Identify the sport which was played in all summer olympics.
7. Which Sports were just played only once in the olympics?
8. Fetch the total no of sports played in each olympic games.
9. Fetch details of the oldest athletes to win a gold medal.
10. Find the Ratio of male and female athletes participated in all olympic games.
11. Fetch the top 5 athletes who have won the most gold medals.
12. Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).
13. Fetch the top 5 most successful countries in olympics. Success is defined by no of medals won.
14. List down total gold, silver and broze medals won by each country.
15. List down total gold, silver and broze medals won by each country corresponding to each olympic games.
16. Identify which country won the most gold, most silver and most bronze medals in each olympic games.
17. Identify which country won the most gold, most silver, most bronze medals and the most medals in each olympic games.
18. Which countries have never won gold medal but have won silver/bronze medals?
19. In which Sport/event, India has won highest medals.
20. Break down all olympic games where india won medal for Hockey and how many medals in each olympic games.

*The problem statements above have been kindly provided by techTFQ and can be found in this [link](https://techtfq.com/blog/practice-writing-sql-queries-using-real-dataset).*

We will be writing the queries on a Jupyter notebook environment and connect it to a local PostgreSQL database. Please find the SQL queries to the above questions [here](https://github.com/tjiacheng123/Analyzing_Olympics_History/blob/main/Analyzing_Olympics_History.ipynb). 

The queries range from easy to complex and some of the notable clauses applied are:
- Joining datasets using INNER JOIN and LEFT JOIN
- Replacing values in dataset using SET
- Tranposing long dataset to wide using CASE WHEN
- Creating temporary datasets and improving readability using WITH
- Ranking medals based on 2 groups using RANK and PARTITION BY
- Concatenating strings using CONCAT

More information and files on the datasets can be found in this [link](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).
