# DuckDB Tools

[DuckDB](https://duckdb.org/docs/) is an in-process SQL [OLAP](https://en.wikipedia.org/wiki/Online_analytical_processing) database management system that uses vectorized data engine and parallel query processing optimized for analytics. DuckDB provides extensive [SQL support](https://duckdb.org/docs/sql/introduction) with direct [data loading](https://duckdb.org/docs/data/overview#csv-loading) and query capabilities for local and remote data sources in `Parquet`, `CSV`, and `JSON` data formats.

[Random Fractals, Inc.](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) created two DuckDB Visual Studio Code IDE extensions that allow you to view and query local data, DuckDB files, and remote data sources: [DuckDB Pro Tools](https://randomfractals.github.io/pro-data-tools/#duckdb-pro-tools) and [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools).

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

## DuckDB SQL Tools Installation

Install [DuckDB SQL Tools](https://github.com/RandomFractals/duckdb-sql-tools) *Preview* extension from [VS Code marketplace](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) or directly in VS Code IDE from Extensions tab (`ctrl+shift+x`) by searching for `DuckDB`.

![DuckDB SQL Tools VS Code Extension Info](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools-extension-info.png?raw=true)

**DuckDB SQL Tools** [Installation](https://github.com/RandomFractals/duckdb-sql-tools#installation) documentation has instructions on how to install this *Preview* extension in [VSCodium](https://vscodium.com/) and other VS Code based IDEs like [Azure Data Studio](https://github.com/Microsoft/azuredatastudio).

**DuckDB SQL Tools** documentation also lists all the [Limitations](https://github.com/RandomFractals/duckdb-sql-tools#limitations) and restrictions of this free public DuckDB VS Code extension *Preview* version, and recommended SQL Tools extension [Configuration](https://github.com/RandomFractals/duckdb-sql-tools#configuration) settings to use with our DuckDB VS Code Tools.

# Pro Data Tools

[**Pro Data Tools**](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) is our new Visual Studio Code extensions pack with premium SQL query and data view features created for the monthly [**Pro sponsors**](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) of our extensions on GitHub.

Our **Pro Data Tools** for devs and data scientists using VS Code IDE include **DuckDB Pro Tools**, [PRQL Code Lens](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) and new [Markdown SQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#markdown-sql-pro-tools).

![Pro Data Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/pro-data-tools.png?raw=true)

**Pro Data Tools** enhance SQL development experience, documentation and notebooks SQL code preview, SQL query execution and results rendering capablities for the different database management systems supported by the SQL Tools extension and plugins.

# DuckDB Pro Tools

**DuckDB Pro Tools** extension adds advanced DuckDB connection features and support to VS Code IDE, and provides database schemas display, DuckDB extensions and settings views, information schema and catalog views, SQL query API and user interfaces integrated with the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) extension, SQL query editor, SQL language server, and VS Code data processing tools.

![DuckDB Pro Tools Views](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-views.gif?raw=true)

## DuckDB Pro Tools Features

The latest version of [DuckDB Pro Tools](https://www.linkedin.com/feed/hashtag/?keywords=duckdbpro) extension adds the following capabilities to VS Code IDE for working with [DuckDB v0.8](https://duckdb.org/2023/05/17/announcing-duckdb-080.html) instances:

- **Connect** to a local DuckDB [v0.8.1](https://github.com/duckdb/duckdb/releases/tag/v0.8.1) instance
- **Create** new in-memory DuckDB instance
- **Import** local and remote `CSV`, `JSON` and `Parquet` data files into in-memory DuckDB instance for exploratory data analysis (EDA)
- **View** DuckDB v0.8.1 databases, schemas, tables, columns, views, indexes, sequences, extensions, settings, functions, types and keywords in SQL Tools Connections Explorer
- **Run** SQL queries on active DuckDB connections
- **Attach** SQLite database files to in-memory DuckDB instances to run analytical queries
- **Query** remote `CSV`, `Parquet`, and `JSON` data files with [DuckDB HTTPFS](https://duckdb.org/docs/extensions/httpfs.html) extension and new [DuckDB JSON](https://duckdb.org/2023/03/03/json.html) extension
- **Create** in-memory DuckDB tables from remote data sources and query results
- **Manage** DuckDB v0.8.1 connections in SQL Tools Connections Explorer
- **Auto-complete** SQL keywords, DuckDB instance schemas, table names, column names, and view names for active DuckDB connections in VS Code SQL editor
- **Save** named SQL query Bookmarks
- **Use** SQL Query History
- **Export** DuckDB query results in `CSV` and `JSON` data formats
- **Use** [PRQL Code Lens](https://github.com/RandomFractals/prql-pro-tools#prql-code-lens) from our new [PRQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) collection to generate and run SQL queries on active DuckDB connection
- **Explore** new `employees.duckdb` demo data, PRQL and SQL sample queries
- **Run** sample `chicago-crimes` and `gbif-observations` [PRQL](https://prql-lang.org/) and SQL queries on GitHub and AWS S3 hosted `parquet` data files
- **Use** new `DuckDB Tools` views and metadata shortcut commands from VS Code `Command Palette...`

## DuckDB Pro Tools Installation

**DuckDB Pro Tools**, [PRQL Code Lens](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) and our new [Markdown SQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#markdown-sql-pro-tools) are available to our [Pro Sponsors](https://github.com/sponsors/RandomFractals) on GitHub.

All of our GitHub **Pro** sponsors get invited as collaborators to our private [Pro Data Tools](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) repositories, and will be notified about the upcoming updates, new releases, additions, and new [Data Notebook Pro Tools](https://randomfractals.github.io/pro-data-tools/#data-notebook-pro-tools) extension we'll be releasing later this summer.

To install **DuckDB Pro Tools**, download the latest `duckdb-pro-tools-x.x.x.vsix` from the attached **Assets** in repository [releases](https://github.com/RandomFractals/duckdb-pro-tools/releases).

Use VS Code IDE [Install from VSIX](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix) feature to install downloaded **DuckDB Pro Tools** extension package in VS Code or any other `VSIX`-compatible IDE. **DuckDB Pro Tools** work in [VSCodium](https://vscodium.com/) too.

![DuckDB Pro Tools VS Code Extension Info](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-tools-extensions.png?raw=true)

The other [DuckDB Sql Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) extension you see in the **Installed** DuckDB extensions image above is our Free Trial public version of **DuckDB Tools** that only supports older DuckDB v0.7.1 and limited set of features, demo DuckDB files and sample queries to run.

## DuckDB Upgrade

If you already have the free public DuckDB SQL Tools installed, and configured new **DuckDBPro** connection to use with this **DuckDB Pro Tools** extension, you'll be prompted to update `duckdb-async` library to v0.8.1 to use the latest DuckDB version and features.

You might need to restart VS Code after duckdb library update for the new DuckDB v0.8.1 connection and queries to work. Below is a quick demo of that DuckDB library update process.

![DuckDB Pro Tools Libraries Update](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-upgrade.gif?raw=true)

**Note**: **DuckDB Pro Tools** use [DuckDB Node.js API](https://github.com/duckdb/duckdb/tree/master/tools/nodejs) and require a local [Node.js installation](https://nodejs.org/en/download) to query DuckDB instances.

Download and install **Node.js** from the official [node.js downloads](https://nodejs.org/en/download) page. Node.js is used as a local web server to host local data and DuckDB files. Node.js will install **npm** tool we use to install `duckdb-async` library to establish DuckDB connections.

We use Node.js DuckDB library instead of the limited DuckDB WASM browser JS library other similar DuckDB data tools use to enable faster data imports and loading via multi-threaded [`node-gyp`](https://github.com/nodejs/node-gyp) DuckDB native API interface.

