1. Gain expertise in SQL joins with tasks that require combining multiple tables to extract meaningful insights. Learners explore INNER JOIN, LEFT JOIN, and FULL OUTER JOIN for various scenarios.
2. Write a query to find all properties where the average rating is greater than 4.0 using a subquery.
3. Write a correlated subquery to find users who have made more than 3 bookings.
4. Write a query to find the total number of bookings made by each user, using the COUNT function and GROUP BY clause.
5. Use a window function (ROW_NUMBER, RANK) to rank properties based on the total number of bookings they have received.
6. Identify high-usage columns in your User, Booking, and Property tables (e.g., columns used in WHERE, JOIN, ORDER BY clauses).
7. Write SQL CREATE INDEX commands to create appropriate indexes for those columns and save them on database_index.sql
8. Measure the query performance before and after adding indexes using EXPLAIN or ANALYZE.
9. Refactor the query to reduce execution time, such as reducing unnecessary joins or using indexing.
10. Analyze the query’s performance using EXPLAIN and identify any inefficiencies.
11. Write an initial query that retrieves all bookings along with the user details, property details, and payment details and save it on perfomance.sql
12. Assume the Booking table is large and query performance is slow. Implement partitioning on the Booking table based on the start_date column. Save the query in a file partitioning.sql
13. Test the performance of queries on the partitioned table (e.g., fetching bookings by date range).
14. Write a brief report on the improvements you observed.
15. Use SQL commands like SHOW PROFILE or EXPLAIN ANALYZE to monitor the performance of a few of your frequently used queries.
16. Identify any bottlenecks and suggest changes (e.g., new indexes, schema adjustments).
17. Implement the changes and report the improvements.
