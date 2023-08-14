# DuckDB Tools

[DuckDB](https://duckdb.org/docs/) is an in-process SQL [OLAP](https://en.wikipedia.org/wiki/Online_analytical_processing) database management system that uses vectorized data engine and parallel query processing optimized for analytics. DuckDB provides extensive [SQL support](https://duckdb.org/docs/sql/introduction) with direct [data loading](https://duckdb.org/docs/data/overview#csv-loading) and query capabilities for local and remote data sources in `Parquet`, `CSV`, and `JSON` data formats.

[Random Fractals, Inc.](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) created two Visual Studio Code IDE extensions that allow you to view and query local data, DuckDB files, and remote data sources using DuckDB: [DuckDB Pro Tools](https://randomfractals.github.io/pro-data-tools/#duckdb-pro-tools) and [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) *Preview*.

![DuckDB VS Code Extensions](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/duckdb-vscode-extensions.png?raw=true)

# DuckDB SQL Tools

The free and public [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) *Preview* VS Code extension adds basic DuckDB SQL support and provides DuckDB connection management, SQL query API and user interfaces for the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) extension, SQL query editor, SQL language server, and data processing tools.

![DuckDB SQL Tools](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools.gif?raw=true)

## DuckDB SQL Tools *Preview* Features

[DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) *Peview* extension v1.1.0 adds the following basic DuckDB SQL capabilities to VS Code IDE for working with DuckDB v0.7.1 instances:

- **Connect** to a local DuckDB v0.7.1 file instance
- **Create** new in-memory DuckDB instance
- **View** DuckDB v0.7.1 tables, columns, and views
- **Run** SQL queries on open DuckDB v0.7.1 connections
- **Attach** SQLite database files to in-memory DuckDB instances
- **Query** remote `CSV` and `Parquet` data files with [DuckDB HTTPFS](https://duckdb.org/docs/extensions/httpfs.html) extension
- **Create** in-memory DuckDB tables from remote data sources and query results
- **Manage** DuckDB connections in SQL Tools Connection Explorer
- **Autocomplete** SQL keywords, table names, column names, and view names in SQL editor for an active DuckDB connection
- **Save** named SQL query Bookmarks
- **Use** SQL Query History
- **Export** SQL query results in `CSV` and `JSON` data formats

[SQL Tools documentation](https://vscode-sqltools.mteixeira.dev/en/home/) contains more information about the other generic SQL Tools extension features.

DuckDB SQL Tools [Installation](https://github.com/RandomFractals/duckdb-sql-tools#installation) documentation provides instructions on how to install this *Preview* extension in VS Code or VS Codium, and lists the current [Limitations](https://github.com/RandomFractals/duckdb-sql-tools#limitations) and restrictions of this free DuckDB VS Code extension version.

# DuckDB Pro Tools

[**Pro Data Tools**](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) is our new Visual Studio Code extensions pack with premium SQL query and data view features created for the monthly [**Pro sponsors**](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) of our extensions on github.

**Pro Data Tools** enhance SQL development experience, documentation and notebooks SQL code preview, SQL query execution and results rendering capablities for the different database management systems supported by the SQL Tools extension and plugins.

**DuckDB Pro Tools** extension adds advanced [DuckDB](https://duckdb.org/) connection features and support to [VS Code](https://code.visualstudio.com/) IDE, and provides database schemas display, DuckDB extensions and settings views, information schema and catalog views, SQL query API and user interfaces integrated with the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) extension, SQL query editor, SQL language server, and VS Code data processing tools.

![DuckDB Pro Tools Views](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-views.gif?raw=true)

## DuckDB Pro Tools *Preview* Features

The latest version of [DuckDB Pro Tools](https://www.linkedin.com/feed/hashtag/?keywords=duckdbpro) extension adds the following capabilities to VS Code IDE for working with [DuckDB v0.8](https://duckdb.org/2023/05/17/announcing-duckdb-080.html) instances:

- **Connect** to a local DuckDB [v0.8.1](https://github.com/duckdb/duckdb/releases/tag/v0.8.1) instance
- **Create** new in-memory DuckDB instance
- **Import** local and remote `CSV`, `JSON` and `Parquet` data files into in-memory DuckDB instance for exploratory data analysis (EDA)
- **View** DuckDB v0.8.0 databases, schemas, tables, columns, views, indexes, sequences, extensions, settings, functions, types and keywords in SQL Tools Connections Explorer
- **Run** SQL queries on active DuckDB connections
- **Attach** SQLite database files to in-memory DuckDB instances to run analytical queries
- **Query** remote `CSV`, `Parquet`, and `JSON` data files with [DuckDB HTTPFS](https://duckdb.org/docs/extensions/httpfs.html) extension and new [DuckDB JSON](https://duckdb.org/2023/03/03/json.html) extension
- **Create** in-memory DuckDB tables from remote data sources and query results
- **Manage** DuckDB v0.8.0 connections in SQL Tools Connections Explorer
- **Auto-complete** SQL keywords, DuckDB instance table names, column names, and view names for active DuckDB connections in VS Code SQL editor
- **Save** named SQL query Bookmarks
- **Use** SQL Query History
- **Export** DuckDB query results in `CSV` and `JSON` data formats
- **Use** [PRQL Code Lens](https://github.com/RandomFractals/prql-pro-tools#prql-code-lens) from our new [PRQL Pro Tools](https://twitter.com/search?q=(%23PRQLProTools)%20(from%3ATarasNovak)&src=typed_query&f=live) collection to generate and run SQL queries on active DuckDB connection
- **Explore** new [`employees.duckdb`](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/employees) demo data, PRQL and SQL sample queries
- **Run** sample [`chicago-crimes`](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/chicago-crimes) and [`gbif-observations`](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/gbif-observations) [PRQL](https://prql-lang.org/) and SQL queries on Github and AWS S3 hosted `parquet` data files
- **Use** new `DuckDB Tools` views and metadata shortcut commands from VS Code `Command Palette...`
