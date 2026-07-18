# AnalystLab Africa — Week 3: SQL & Data Querying

Data analytics internship task covering SQL database setup, querying, joins, subqueries, window functions, business problem solving, and query optimization across two datasets.

## 📊 Datasets
- **Chinook Database** (music store, 11 relational tables) — [source](https://github.com/lerocha/chinook-database)
- **Sample Sales Data** (flat sales transactions table) — [source](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

## 🔍 What was done
- Imported both datasets into MySQL and documented schema relationships
- Wrote 25 total SQL queries covering SELECT/WHERE/ORDER BY, GROUP BY/HAVING, aggregate functions, JOINs, subqueries, and window functions (RANK, ROW_NUMBER, PARTITION BY)
- Solved real business questions: top customers, revenue trends, product/genre performance, regional analysis, employee performance
- Caught and corrected a data validation issue — an apparent "revenue decline" that was actually caused by incomplete year-over-year date coverage
- Tested query optimization via indexing on both datasets, comparing results on a small table (412 rows, index not used) versus a larger table (2,755 rows, index successfully used)

## 📁 Files
| File | Description |
|---|---|
| `chinook_queries.sql` | Full SQL script: schema notes, 14 queries, and indexing optimization test (Chinook) |
| `sales_queries.sql` | Full SQL script: schema notes, 11 queries, and indexing optimization test (Sales Data) |
| `Chinook_SQL_Documentation.docx` | Query documentation and business insights (Chinook) |
| `SalesData_SQL_Documentation.docx` | Query documentation and business insights (Sales Data) |

## 🛠️ Tools
MySQL, MySQL Workbench
