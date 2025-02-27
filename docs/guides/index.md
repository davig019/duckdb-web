---
layout: docu
title: Guides
---

The guides section contains compact how-to guides that are focused on achieving a single goal. For an in-depth reference see the Documentation section.

Note that there are many tools using DuckDB, which are not covered in the official guides. To find a list of these tools, check out the [Awesome DuckDB repository](https://github.com/davidgasquez/awesome-duckdb).

## Data Import and Export

### CSV Files

* [How to load a CSV file into a table](../guides/import/csv_import)
* [How to export a table to a CSV file](../guides/import/csv_export)

### Parquet Files

* [How to load a Parquet file into a table](../guides/import/parquet_import)
* [How to export a table to a Parquet file](../guides/import/parquet_export)
* [How to run a query directly on a Parquet file](../guides/import/query_parquet)

### HTTP(S), S3 and GCP

* [How to load a Parquet file directly from HTTP(S)](../guides/import/http_import)
* [How to load a Parquet file directly from S3 or GCS](../guides/import/s3_import)
* [How to load an Iceberg table directly from S3](../guides/import/s3_iceberg_import)
 
### JSON Files

* [How to load a JSON file into a table](../guides/import/json_import)
* [How to export a table to a JSON file](../guides/import/json_export)

### Excel Files with the Spatial Extension

* [How to load an Excel file into a table](../guides/import/excel_import)
* [How to export a table to an Excel file](../guides/import/excel_export)

### Querying Other Database Systems

* [How to directly query a PostgreSQL database](../guides/import/query_postgres)
* [How to directly query a SQLite database](../guides/import/query_sqlite)
* [How to directly query a MySQL database](../guides/import/query_mysql)

## Performance

* [My workload is slow (troubleshooting guide)](../guides/performance/my_workload_is_slow)
* [How to design the schema for optimal performance](../guides/performance/schema)
* [What is the ideal hardware environment for DuckDB](../guides/performance/environment)
* [What performance implications do Parquet files and (compressed) CSV files have](../guides/performance/file_formats)
* [How to tune workloads](../guides/performance/how_to_tune_workloads)
* [Benchmarks](../guides/performance/benchmarks)

## Meta Queries

* [How to list all tables](../guides/meta/list_tables)
* [How to view the schema of the result of a query](../guides/meta/describe)
* [How to quickly get a feel for a dataset using summarize](../guides/meta/summarize)
* [How to view the query plan of a query](../guides/meta/explain)
* [How to profile a query](../guides/meta/explain_analyze)

## ODBC

* [How to set up an ODBC application (and more!)](../guides/odbc/general)

## Python Client

* [How to install the Python client](../guides/python/install)
* [How to execute SQL queries](../guides/python/execute_sql)
* [How to easily query DuckDB in Jupyter Notebooks](../guides/python/jupyter)
* [How to use Multiple Python Threads with DuckDB](../guides/python/multiple_threads)
* [How to use fsspec filesystems with DuckDB](../guides/python/filesystems)

### Pandas

* [How to execute SQL on a Pandas DataFrame](../guides/python/sql_on_pandas)
* [How to create a table from a Pandas DataFrame](../guides/python/import_pandas)
* [How to export data to a Pandas DataFrame](../guides/python/export_pandas)

### Apache Arrow

* [How to execute SQL on Apache Arrow](../guides/python/sql_on_arrow)
* [How to create a DuckDB table from Apache Arrow](../guides/python/import_arrow)
* [How to export data to Apache Arrow](../guides/python/export_arrow)

### Relational API

* [How to query Pandas DataFrames with the Relational API](../guides/python/relational_api_pandas)

### Python Library Integrations

* [How to use Ibis to query DuckDB with or without SQL](../guides/python/ibis)
* [How to use DuckDB with Polars DataFrames via Apache Arrow](../guides/python/polars)

## SQL Features

* [As-of join](../guides/sql_features/asof_join)
* [Full-text search](../guides/sql_features/full_text_search)

## SQL Editors and IDEs

* [How to set up the DBeaver SQL IDE](../guides/sql_editors/dbeaver)

## Data Viewers

* [How to visualize DuckDB databases with Tableau](../guides/data_viewers/tableau)
* [How to draw command-line plots with DuckDB and YouPlot](../guides/data_viewers/youplot)
