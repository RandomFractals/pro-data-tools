# DuckDB Tools

[DuckDB](https://duckdb.org/docs/) is an in-process SQL [OLAP](https://en.wikipedia.org/wiki/Online_analytical_processing) database management system that uses vectorized data engine and parallel query processing optimized for analytics. DuckDB provides extensive [SQL support](https://duckdb.org/docs/sql/introduction) with direct [data loading](https://duckdb.org/docs/data/overview#csv-loading) and query capabilities for local and remote data sources in `Parquet`, `CSV`, and `JSON` data formats.

[Random Fractals, Inc.](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) created two DuckDB Visual Studio Code IDE extensions that allow you to view and query local data, DuckDB files, and remote data sources: [DuckDB Pro Tools](https://randomfractals.github.io/pro-data-tools/#duckdb-pro-tools) and [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools).

![DuckDB VS Code Extensions](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/duckdb-vscode-extensions.png?raw=true)

# DuckDB SQL Tools

The free and public [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) *Preview* VS Code extension adds basic DuckDB SQL support and provides DuckDB connection management, SQL query API and user interfaces for the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) extension, SQL query editor, SQL language server, and data processing tools.

![DuckDB SQL Tools](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools.gif?raw=true)

## DuckDB SQL Tools *Preview* Features

[DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) *Preview* extension v1.2.0 adds the following basic DuckDB SQL capabilities to VS Code IDE for working with DuckDB v0.8.1 instances:

- **Connect** to a local DuckDB v0.8.1 file instance
- **Create** new in-memory DuckDB instance
- **View** DuckDB v0.8.1 tables, columns, and views
- **Run** SQL queries on open DuckDB v0.8.1 connections
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

Our **Pro Data Tools** for devs and data scientists using VS Code IDE include **DuckDB Pro Tools**, [PRQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) and new [Markdown SQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#markdown-sql-pro-tools).

![Pro Data Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/pro-data-tools.png?raw=true)

**Pro Data Tools** enhance SQL development experience, documentation and notebooks SQL code preview, SQL query execution and results rendering capablities for the different database management systems supported by the SQL Tools extension and plugins.

# DuckDB Pro Tools

**DuckDB Pro Tools** extension adds advanced DuckDB connection features and support to VS Code IDE, and provides database schemas display, DuckDB extensions and settings views, information schema and catalog views, SQL query API and user interfaces integrated with the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) extension, SQL query editor, SQL language server, and VS Code data processing tools.

![DuckDB Pro Tools Views](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-views.gif?raw=true)

## DuckDB Pro Tools Features

The latest version of [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) extension adds the following capabilities to VS Code IDE for working with [DuckDB v0.8](https://duckdb.org/2023/05/17/announcing-duckdb-080.html) instances:

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
- **Use** over 30 built-in `DuckDB Tools` views and metadata shortcut commands from VS Code `Command Palette...`

## DuckDB Pro Tools Installation

Become a [Pro Sponsor](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) of our new **Pro Data Tools** work on GitHub to access **DuckDB Pro Tools**, [PRQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) and our new [Markdown SQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#markdown-sql-pro-tools) releases and extension `.vsix` installation packages.

All of our GitHub **Pro** sponsors get invited as collaborators to our private [Pro Data Tools](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) repositories, and will be notified about the upcoming updates, new releases, additions, and new [Data Notebook Pro Tools](https://randomfractals.github.io/pro-data-tools/#data-notebook-pro-tools) extension we'll be releasing later this year.

To install **DuckDB Pro Tools**, download the latest `duckdb-pro-tools-x.x.x.vsix` from the attached **Assets** in repository [releases](https://github.com/RandomFractals/duckdb-pro-tools/releases).

Use VS Code IDE [Install from VSIX](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix) feature to install downloaded **DuckDB Pro Tools** extension package in VS Code or any other `VSIX`-compatible IDE. **DuckDB Pro Tools** work in [VSCodium](https://vscodium.com/) and the latest version of [Azure Data Studio](https://github.com/Microsoft/azuredatastudio) IDE.

![DuckDB Pro Tools VS Code Extension Info](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-tools-extensions.png?raw=true)

The other [DuckDB Sql Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) extension you see in the **Installed** DuckDB extensions image above is our Free Trial public version of **DuckDB Tools** that only supports older DuckDB v0.8.1 and limited set of features, demo DuckDB files and sample queries to run.

## DuckDB Upgrade

If you already have the free public DuckDB SQL Tools installed, and configured new **DuckDBPro** connection to use with **DuckDB Pro Tools** extension, you'll be prompted to update `duckdb-async` library to v0.8.1 to use the latest DuckDB version and features.

You might need to restart VS Code after duckdb library update for the new DuckDB v0.8.1 connection and queries to work. Below is a quick demo of that DuckDB library update process.

![DuckDB Pro Tools Libraries Update](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-upgrade.gif?raw=true)

**Note**: **DuckDB Pro Tools** use [DuckDB Node.js API](https://github.com/duckdb/duckdb/tree/master/tools/nodejs) and require a local [Node.js installation](https://nodejs.org/en/download) to query DuckDB instances.

Download and install **Node.js** from the official [node.js downloads](https://nodejs.org/en/download) page. Node.js is used as a local web server to host local data and DuckDB files. Node.js will install **npm** tool we use to install `duckdb-async` library to establish DuckDB connections.

We use Node.js DuckDB library instead of the limited DuckDB WASM browser JS library other similar DuckDB data tools use to enable faster data imports and loading via multi-threaded [`node-gyp`](https://github.com/nodejs/node-gyp) DuckDB native API interface.

# DuckDB Objects Tree View

**DuckDB Pro Tools** v1.1.0 and higher now display the full catalog of DuckDb instance objects to view and query from SQL Tools Connections Explorer. The extended DuckDB objects tree view includes main DuckDB instance, `system`, and `temp` databases with the corresponding `main`, [`information_schema`](https://duckdb.org/docs/sql/information_schema) and [`pg_catalog`](https://www.postgresql.org/docs/current/catalogs-overview.html) schemas.

![DuckDB Pro Tools DB Tree View](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-db-tree-view.gif?raw=true)

## PG Catalog

DuckDB provides many standard PostgreSQL [`pg_catalog`](https://www.postgresql.org/docs/current/catalogs-overview.html) functions and views for compatibility with PostgreSQL database and SQL syntax. You can explore those internal DuckDB views and function signatures via `pg_catalag` schema in the DuckDB Objects tree view.

![DuckDB Pro Tools PG Catalog](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-pg-catalog-functions.png?raw=true)

## DuckDB Objects and Views

**DuckDB Pro Tools** v1.1.0 and higher DB Objects tree view also shows the full list of DuckDB [indexes](https://duckdb.org/docs/sql/indexes), [sequences](https://duckdb.org/docs/sql/statements/create_sequence), [`information_schema`](https://duckdb.org/docs/sql/information_schema#database-catalog-and-schema) and other custom `duckdb` [metadata functions](https://duckdb.org/docs/sql/duckdb_table_functions) and internal views.

![DuckDB Pro Tools Views](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-views.gif?raw=true)

### DuckDB Views

![DuckDB Pro Tools Views](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-internal-views.png?raw=true)

### Indexes

![DuckDB Pro Tools Indexes](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-indexes-view.png?raw=true)

### Sequences

![DuckDB Pro Tools Sequences](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-sequences-view.png?raw=true)

### Extensions

![DuckDB Pro Tools Extensions](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-extensions-tree-view.png?raw=true)

### Functions

![DuckDB Pro Tools DB Functions](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-functions-tree-view.png?raw=true)

### DuckDB Types

![DuckDB Pro Tools DB Types](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-types-tree-view.png?raw=true)

### DuckDB SQL Keywords

![DuckDB Pro Tools SQL Keywords](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-keywords-tree-view.png?raw=true)

## Configuration Settings

New DuckDB [configuration settings](https://duckdb.org/docs/sql/configuration) display with setting type icons and current values in the DuckDB Objects tree view item description.

![DuckDB Configuration Settings Tree View](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-settings-tree-view.png?raw=true)

## Table and View Columns

DuckDB configuration settings, database schema types, table and view columns now show basic data type icons for strings, numeric, date and timestamp columns and setting types.

![DuckDB Table and View Columns](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-columns-view.png?raw=true)

Additionally, **DuckDB Pro Tools** v1.1.0 and higher display primary columns in tables, and `not null` column value constraints.

# DuckDB View Commands

**DuckDB Pro Tools** v1.2.0 added over 30 built-in DuckDB views and metadata shortcut commands to the Command Palette you can access via `ctrl/cmd+shift+p` shortcut in VS Code or from `View -> Commnad Palette...` menu by typing `DuckDB Tools` in the `>` command prompt:

![DuckDB Tools View Commands](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-view-commands.gif?raw=true)

# DuckDB Extensions

DuckDB egnine itself provides a number of [Extensions](https://duckdb.org/docs/extensions/overview) you can install and load to work with local and remote `CSV` and `Parquet` data files over [HTTPFS](https://duckdb.org/docs/extensions/httpfs), enable [Full Text Search](https://duckdb.org/docs/extensions/full_text_search), attach [SQLite](https://sqlite.org/about.html) database with [SQLite Scanner](https://duckdb.org/docs/extensions/sqlite_scanner), or attach [PostgreSQL](https://www.postgresql.org/about/) database instance with DuckDB [Postgres Scanner](https://duckdb.org/docs/extensions/postgres_scanner).

You can check the list of core and installed DuckDB extensions by running the following SQL query on an open/active DuckDB connection:

```sql
select * from duckdb_extensions();
```

![DuckDB Pro Tools DuckDB Extensions](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-duckdb-extensions.png?raw=true)

## DuckDB JSON

[DuckDB v0.7](https://duckdb.org/2023/02/13/announcing-duckdb-070.html) and higher DuckDB `v0.8.1` include new and improved [`JSON` extension](https://duckdb.org/2023/03/03/json.html) capabilities to work with JSON documents. **DuckDB Pro Tools** install and load DuckDB JSON extension for all active DuckDB conenctions in order to enable quick JSON data imports and other JSON related features without extra SQL setup.

Quick DuckDB JSON extension query example and steps to parse and load remote `JSON` data document from a public Github repository with **DuckDB Pro Tools** in VS Code:

⥱ Create new in-memory DuckDBPro config.

⥱ Use JSON data http://raw.githubusercontent.com URL in your SELECT statement.

⥱ Optionally use `CREATE TABLE ... AS` SQL statement to load retrieved `JSON` data into new DuckDB table and run multiple queries on that data loaded into memory.

![DuckDB Pro Tools JSON Data Load](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-json-data-load.gif?raw=true)

**Note**: the US airports demo data in example above is from our VS Code [Data Table Renderers](https://github.com/RandomFractals/vscode-data-table/tree/main/data) extension we will use later in the upcoming [Data Notebook Pro](https://twitter.com/search?q=(%23DataNotebook)%20(from%3ATarasNovak)&src=typed_query&f=live) extension to query and display tabular data results from many different data sources, including DuckDB. New **Data Notebook Pro** extension will be released in Q4 of 2023.

Quick Data Notebook extension info preview with a simple Data Connections side panel and a few commands already implemented for that custom VS Code Notebook extension we plan to release with SQL and PRQL queries support.

![Data Notebook Pro Extension Info](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/data-notebook-extension.png?raw=true)

## DuckDB HTTPFS

**DuckDB Pro Tools** extension also installs and loads [HTTPFS](https://duckdb.org/docs/extensions/httpfs) DuckDB extension by default for all the open database instances. You can add other [DuckDB Extensions](https://duckdb.org/docs/extensions/overview) to an open database instance by running [`INSTALL` and `LOAD`](https://duckdb.org/docs/extensions/overview#remote-installation) extension SQL statements.

Example of loading trimmed down Chicago crimes data reported in 2022 into an in-memory DuckDB instance from a `.parquet` data file hosted in our [Chicago Crimes](https://github.com/RandomFractals/chicago-crimes) data and analytical tools demo Github repository:

![DuckDB Pro Tools HTTPFS](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools-httpfs-data-load.gif?raw=true)

This example uses implicitly loaded DuckDB HTTPFS extension to query reported Chicago crimes parquet data file with over 210K recorded crime reports, creates a `CrimeReports` table in a new DuckDB `:memory:` instance from remote parquet data file, and queries imported data.

## DuckDB SQLite Scanner

[SQLite](https://sqlite.org/about.html) database users can use **DuckDB Pro Tools** VS Code extension and DuckDB [SQLite Scanner](https://duckdb.org/docs/extensions/sqlite_scanner) extension to add data from SQLite database to in-memory DuckDB instance.

Run the following SQL statements to add SQLite Scanner DuckDB extension to an open database connection:

```sql
INSTALL sqlite;
LOAD sqlite;
```

With the loaded SQLite Scanner DuckDB extension you can attach SQLite database file to a DuckDB database instance. Attached SQLite database tables will show up as views in DuckDB instance.

Run the following SQL `CALL` function to attach SQLite database instance:

```sql
CALL sqlite_attach('E:\\projects\\data\\tools\\duckdb-tools\\data\\chinook\\sqlite\\chinook.sqlite');
```

![DuckDB Pro Tools SQLite Scanner](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools-sqlite-scanner.gif?raw=true)

## DuckDB File References

**Note**: **DuckDB Pro Tools** extension uses [DuckDB NodeJS Client API](https://duckdb.org/docs/api/nodejs/overview). In order to work with local data files, you need to specify full path to your local database or data files in SQL statements that reference local file paths.

Future versions of this extension will simplify local file path references by deducing absolute file path from the local DuckDB file connection string or open VS Code project workspace folder path, and replace relative database or data file references with the corresponding absolute path in an open VS Code project workspace.

Also, note in the `sqlite_attach()` SQL function call statement above we are escaping `\` file path delimiters on Windows OS by using `\\` characters sequence.

# Demo Data

**DuckDB Pro Tools** extension documentation repository contains sample [/data](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/chinook/duckdb) folder with the popular [`chinook.duckdb`](https://github.com/RandomFractals/duckdb-pro-tools/blob/main/data/chinook/duckdb/chinook.duckdb) and [`chinook.sqlite`](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/data/chinook/sqlite/chinook.sqlite) database files you can experiment with.

This private beta repository also contains new SQL scripts, create demo DuckDB files Jupyter notebooks, `schema.sql` and `load.sql` DuckDB scripts with demo `CSV` and `Parquet` data files, and new PRQL and SQL query examples for [Chicago Crimes](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/chicago-crimes), [Employees](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/employees), [GBIF Observations](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/gbif-observations), [TPC-DS](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/tpc-ds) and [TPC-H](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/tpc-h) benchmarks, and some public [Transporation](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data/transportation) datasets query examples our Pro sponsors on github can use to get started with **DuckDB Pro Tools** in VS Code.

![DuckDB Pro Tools Demo Data](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-data.png?raw=true)

## SQL Query Examples

The demo [`/data`](https://github.com/RandomFractals/duckdb-pro-tools/tree/main/data) folder contains sample `.sql` files with SQL and PRQL query examples you can try. You can also easily generate new SQL queries using recently released [Hugging Face Code Autocomplete](https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode) VS Code extension.

For example, SQL queries in [employees/prompt.sql](https://github.com/RandomFractals/duckdb-pro-tools/blob/main/data/employees/prompt.sql) were generated with HF Code Autocomplete.

![DuckDB SQL Code Autocomplete](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-prompt-queries-gen.gif?raw=true)

![DuckDB Prompt Queries Run](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-pro-tools-employees-prompt-queries.gif?raw=true)

We'll add more demo data, sample DuckDB files, PRQL and SQL query examples in future **DuckDB Pro Tools** releases.

# Limitations

While **DuckDB Pro Tools** offer more features and examples, and work with the latest version of DuckDB, there are still some limitations in the initial version of this extension which we plan to address in the upcoming monthly updates and releases.

## DuckDB Storage

The latest version of **DuckDB Pro Tools** extension supports local DuckDB instances created with [DuckDB v0.8.1](https://github.com/duckdb/duckdb/releases) engine. Database instances and files created with prior versions of DuckDB are not supported as they use different compression and [storage](https://duckdb.org/internals/storage) formats and the structure of `.duckdb` file has been changing as DuckDB engine is evolving.

You can still use our free limited capabilities public [DuckDB SQL Tools](https://github.com/RandomFractals/duckdb-sql-tools) extension to load and query older DuckDB v0.6.1 data files. Switching between older DuckDB Sql Tools and this **DuckDB Pro Tools** version and DuckDB file configs will prompt you to upgrade or downgrade the corresponding DuckDB Node.js library accordingly, but you can keep both extensions and switch the extension you want to use depending on the DuckDB files version you are working with.

Otherwise, Use [DuckDB CLI](https://duckdb.org/docs/api/cli.html) to export data from the older database file versions and create new `.duckdb` file using the latest DuckDB storage implemenation.

Read [Announcing DuckDB 0.6.0](https://duckdb.org/2022/11/14/announcing-duckdb-060.html), [Announcing DuckDB 0.7.0](https://duckdb.org/2023/02/13/announcing-duckdb-070.html), and [Announcing DuckDB 0.8.0](https://duckdb.org/2023/05/17/announcing-duckdb-080.html) blog posts for more information about DuckDB storage improvements, new features, and other changes.

## DuckDB Read/Write

**DuckDB Pro Tools** extension v1.1.0 and above now open `.duckdb` database files in `read-write` file access mode.

**NOTE**: current DuckDB write access mode and connection handling in **DuckDB Pro Tools** v1.1.0 and latest is very alpha and some restrictions still apply:

- DuckDB v0.8.1 still supports only **one** active `write` connection, or multipple `readers` and no `writers` in its latest implementation.

- DuckDB Pro Tools will create a `read-only` connection if opening `.duckdb` file in `read-write` access mode fails.

- Additionally, we now add [`PRAGMA enable_checkpoint_on_shutdown`](https://duckdb.org/docs/sql/pragmas#enable_checkpoint_on_shutdown-disable_checkpoint_on_shutdown) to all open DuckDB connections to run [`checkpoint`](https://duckdb.org/docs/sql/statements/checkpoint) when all DuckDB connecitons are closed and the parent NodeJS process releases a lock on the `.wal` write ahead log file in order to synchronize all writes and database updates to the main `.duckdb` file.

**Important**: we recommend you don't close open DuckDB connections via SQL Tools Connections close context menu and let VS Code, NodeJS, and DuckDB processes handle data sync from `.wal` files on shutdown.

**DuckDB Pro Tools** let you open multiple DuckDB connections while keeping only one DuckDB connection as current or active when you select that connection in SQL Tools Connections Explorer view. If you close an active DuckDB connection and get an error while trying to reconnect, we suggest you **restart VS Code** for DuckDB to release `.wal` file lock and grant new write or read-only database file access.

We are working on a new custom DuckDB Connection Pooling interface that will handle DuckDB connections better, and will prompt you to close another write connection open by another process or a program, when the DuckDB `.wal` file is detected or locked by another process for the local DuckDB instance you attempt to update.

## In-Memory DuckDB

**DuckDB Pro Tools** extension lets you create in-memory database instances by specifying `:memory:` keyword in the Database File field of the new DuckDB connection in SQL Tools Connection Assistant as demonstrated in DuckDB HTTPFS and SQLite Scanner extension usage examples above.

You can leverage writable `:memory:` DuckDB instances in **DuckDB Pro Tools** to a great extent considering they allow you to load and query remote data files and export data as needed, as demonstrated in `JSON`, `HTTPFS` and other examples above.

In-Memory DuckDB instances function similar to [In-Memory SQLite Databases](https://www.sqlite.org/inmemorydb.html). You can use [DuckDB Import Data](https://duckdb.org/docs/data/overview) and [Atach](https://duckdb.org/docs/sql/statements/attach) features available via DuckDB SQL statements, and use [Export Database](https://duckdb.org/docs/sql/statements/export) SQL statements to export created in-memory DuckDB instances.

## VS Code Memory Limit

You can adjust the amount of RAM allocated to VS Code IDE to enable opening large files and load more data into memory. Go to `File -> Preferences -> Settings` and type `files.maxMemoryForLargeFilesMB` in the Setting search field to change it. For example, users with 64GB of RAM can change it to `49152` MB to allow VS Code use 48GB of available memory.

![VS Code Max Memory Setting](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/vscode-max-memory-setting.png?raw=true)

# Configuration

[SQL Tools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) extension provides many configuration [Settings](https://vscode-sqltools.mteixeira.dev/en/settings/) users can toggle to change database connection and tree view display options, sql formatting, and results display.

The following [SQL Tools Settings](https://vscode-sqltools.mteixeira.dev/en/settings/) were used while creating and testing **DuckDB Pro Tools** extension and are recommended for working with DuckDB instances efficiently. We suggest you set these preferences in User Settings in VS Code by navigating to `File -> Preferences -> Settings -> User -> Extensions -> SQLTools`, or adding them to your global VS Code `settings.json` config file using the JSON code snippet below:

```json
{
  ...
  "sqltools.useNodeRuntime": true,
  "sqltools.disableNodeDetectNotifications": true,
  "sqltools.autoOpenSessionFiles": false,
  "sqltools.results.limit": 10000,
  "sqltools.results.location": "current",
}
```

| Setting | Description |
| --- | --- |
| ```"sqltools.useNodeRuntime": true``` | Enable Node runtime in order to use [DuckDB NodeJS API](https://github.com/duckdb/duckdb/tree/master/tools/nodejs) this database SQL tools extension depends on. |
| ```"sqltools.disableNodeDetectNotifications": true``` | Disable Node runtime detection notifications after initial SQLTools extension installation to prevent Node runtime information message display on every new VS Code session start. |
| ```"sqltools.autoOpenSessionFiles": false``` | Prevent auto open of new session SQL editor instance after connecting to the databaase instance. |
| ```"sqltools.results.limit": 10000``` | Maximum number of records to return in results. SQL Tools defaults to displaying only 50 records in query results view. Changing this limit setting to 1000 or 10000 will show more data rows to inspect in result views. |
| ```"sqltools.results.location": "current"``` | Defines the editor group to use for result table views. SQL Tools displays all results in the next editor group to show results on the side next to the active SQL query editor. Changing this setting to `current` will display results in the same editor group and display more result columns. |

# Feedback

Please use our [DuckDB SQL Tools GitHub Discussions](https://github.com/RandomFractals/duckdb-sql-tools/discussions) portal to submit your feedback, share examples of how you are using our DuckDB VS Code extensions, or request new trivial and premium features. Our goal with these DuckDB SQL and Pro Data Tools extensions is to make DuckDB more accessible and easier to use in VS Code IDE.

# Support

Become a [Fan or a Pro Sponsor](https://github.com/sponsors/RandomFractals) on GitHub to support our dev work on these DuckDB Tools and other [Random Fractals, Inc. code and data viz extensions](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) if you find them useful, educational, or enhancing your daily dataViz dev code workflows and exploratory data analysis experience.

💖 [https://github.com/sponsors/RandomFractals](https://github.com/sponsors/RandomFractals)
