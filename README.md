# Description
Used to generate SQL statement for different data source, e.g MySQL, Presto, Clickhouse, Druid. Provide the functions as below:
- Provide the framework to customize the SQL clauses generation, e.g customize the select clause, join clause.
- Define the caclulation POJO once, and can generate with different dialects(Mysql, Presto, CK, Druid)
