# PRQL Pro Tools

**PRQL Pro Tools** is a collection of custom [PRQL](https://prql-lang.org/) extensions integrated with the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) database management system and plugins to use in VS Code IDE.

![PRQL Code Lens](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-code-lens.gif?raw=true)

## PRQL

[PRQL](https://prql-lang.org/) is a modern language for transforming data. PRQL is database agnostic and compiles to many SQL dialects for the target database management system as described in [PRQL Book](https://prql-lang.org/book).

![PRQL Showcase](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-showcase.png?raw=true)

PRQL tools include [PRQL VS Code](https://marketplace.visualstudio.com/items?itemName=PRQL-lang.prql-vscode) extension that adds PRQL language support, SQL Preview and other PRQL related settings and features to work with it in VS Code IDE.

![PRQL VS Code Extension](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-vscode-extension.png?raw=true)

## SQL Tools

[SQL Tools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) provide connections to many commonly used databases in VS Code. SQL Tools come with many built-in database drivers and an extensive list of community [drivers](https://marketplace.visualstudio.com/search?term=tag%3Asqltools-driver&target=VSCode&category=All%20categories&sortBy=Rating) users can use to connect to the database management system of their choosing, view database objects in SQL Tools Connection Explorer, and run SQL queries.

![SQL Tools Drivers](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/sql-tools-drivers.png?raw=true)

Most of the SQL Tools database drivers use the target database management system browser JavaScript API to connect to the local database server or remote database instances via SQL Tools Connection Assistant user interface:

![SQL Tools Connection Assistant](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/sqltools-connection-assistant.png?raw=true)

Some of the SQL Tools extensions, such as [SQLite](https://vscode-sqltools.mteixeira.dev/en/drivers/sq-lite/) and [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) require [NodeJS](https://nodejs.org/en/download/) installation and `sqltools.useNodeRuntime` setting enabled for tighter inegration of the native database api and access to the local file system to load and view file-based database instances using NodeJS server for the database files and local data files hosting runtime.

![DuckDB Pro Tools Connection](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools-connection.png?raw=true)

## PRQL Pro Tools Extension Pack

**PRQL Pro Tools** is a private beta collection of custom PRQL VS Code extensions for our monthly [**Pro**](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) supporters on github, and can be viewed as an extension pack to enhance PRQL development and runtime workflow connected to the different database management system via SQL Tools extension and database plugins.

## PRQL Code Lens

The initial private beta release of **PRQL Pro Tools** comes with **PRQL Code Lens** extension that allows you to run PRQL queries for the supported PRQL target [SQL dialects](https://prql-lang.org/book/project/target.html#dialects) **directly** against any of the supported SQL Tools extensions and database management systems.

![PRQL Code Lens](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-code-lens.png?raw=true)

### Supported Databases

You can explore [SQL Tools drivers](https://marketplace.visualstudio.com/search?term=tag%3Asqltools-driver&target=VSCode&category=All%20categories&sortBy=Rating) in VS Code Marketplace and install the corresponding database drivers depending on target database management system you intend to use with **PRQL Code Lens** and [SQL Tools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools).

We recommend you install [SQLite](https://vscode-sqltools.mteixeira.dev/en/drivers/sq-lite/) or [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) to get started.

### Configuration

**PRQL Code Lens** uses the corresponding [PRQL Settings](https://github.com/prql/prql-vscode#prql-settings) and `prql.target` for the target database management system when creating SQL query to run at runtime.

See [SQL Tools Settings](https://vscode-sqltools.mteixeira.dev/en/settings/) documentation and specific SQL Tools driver settings to manage SQL query results display and other database specific settings. For example, [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) list some of them in the [Configuration](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#configuration) section.

### Demo Data

**DuckDB SQL Tools** repository has [sample `/data`](https://github.com/RandomFractals/duckdb-sql-tools/tree/main/data) folder you can use to download SQLite and DuckDB demo `chinook` database files and sample PRQL queries you can run.

![Chinook DB Data and Queries](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/duckdb-sql-tools-data.png?raw=true)

**PRQL Pro Tools** repository also has `/data` folder with sample `employees` database data files, schema and load SQL scripts, `create-employees-duckdb.ipynb` Jupyter notebook, and some PRQL query samples you can download, load and run with **PRQL Code Lens**. More `chinook` and `employees` database PRQL sample queries will be added later.

## PRQL Query Examples

Base [PRQL VScode](https://github.com/PRQL/prql-vscode) extension has a few new PRQL [examples](https://github.com/PRQL/prql-vscode/tree/main/examples) that demo new [PRQL compiler v0.6](https://github.com/PRQL/prql/releases) features such as `loop`, `case`, `func` and using variables with `let`.

We also recently added a couple of [GBIF](https://github.com/gbif/occurrence/blob/master/aws-public-data.md) dataset [PRQL query examples](https://github.com/RandomFractals/duckdb-sql-tools/tree/main/data/gbif) to demo loading and querying remote public datasets hosted by AWS with **PRQL Code Lens** extension and [DuckDB SQL Tools](https://github.com/RandomFractals/duckdb-sql-tools):

![GBIF PRQL DuckDB Pro Tools Examples](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/gbif-top-10-duck-species-observations-prql.gif?raw=true)

## PRQL Notebook

Future versions of **PRQL Pro Tools** will include custom **PRQL Notebook** extension integrated with SQL Tools extension, supported database management systems, our [Data Table Renderers](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.vscode-data-table) and VS Code Notebooks user interface to view and run PRQL queries from `.prql` file using Notebook UI:

![PRQL Notebook](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-notebook.png?raw=true)


## PRQL Terminal

We also plan to release a custom version of **PRQL Terminal** extension as part of the **PRQL Pro Tools** extension pack for our monthly [**Pro**](https://github.com/sponsors/RandomFractals/sponsorships?sponsor=RandomFractals&tier_id=18884) supporters later this year.

**PRQL Terminal** will have a walk-through to install `prqlc` CLI tools and will integrate it with the built-in VS Code File Manager and Terminal panel to run PRQL queries from the command line with VS Code commands, shortcuts, and `.prql` file context menus for the CLI fans.

![PRQL Terminal](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/prql-terminal.png?raw=true)

## Installation and Support

You can get access to **PRQL Pro Tools** by becoming a [**Pro** sponsor](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) of our **Pro Data Tools** work on GitHub.

All Pro sponsors get invited as collaborators to our private [Pro Data Tools](https://github.com/RandomFractals/pro-data-tools/tree/main#pro-data-tools) repositories, and will be notified about the upcoming updates, new releases, additions, and new [Data Notebook Pro](https://github.com/RandomFractals/pro-data-tools/tree/main#data-notebook-pro-tools) extension we'll be releasing later this year.

Help us reach our goal of getting 20 Pro monthly sponsors on GitHub. 🙏

💖 https://github.com/sponsors/RandomFractals
