# Data Management for Big Data

The exercise for the Data Management for Big Data exam focused on imple-
menting and optimizing two specific query schemas on the TPC-H bench-
mark using PostgreSQL: Query Schema 1, which analyzes export/import
revenue values, and Query Schema 3, which calculates returned item losses.
These query schemas involved complex aggregations and calculations per-
formed on large datasets, aiming to provide valuable insights into the com-
pany’s operations.
The project’s optimization strategy involved analyzing the query cost
before optimization and comparing it with the costs after applying indexes
and materialized views. The benefits of indexing and materialization in
terms of query performance were assessed separately and in combination.
In the optimization process of the TPC-H benchmark project, we em-
ployed various techniques to enhance the performance of Query Schema 1
and Query Schema 3. To improve query execution, indexing was utilized
to expedite data retrieval and reduce the need for full table scans. Indexes
were designed based on the attributes involved in filtering, grouping, and
joining operations. These indexes facilitated efficient access to the relevant
data, resulting in faster query processing.
Furthermore, materialized views were employed to precompute and store
the results of complex queries. By creating materialized views, we reduced
the need to recompute the same aggregations repeatedly, improving query
response times. Materialized views served as a form of data caching, al-
lowing subsequent queries to retrieve results directly from the precomputed
views.
