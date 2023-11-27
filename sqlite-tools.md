# SQLite Pro Tools

**SQLite Pro Tools** extension adds advanced [SQLite](https://www.sqlite.org/) database connection features and support to [VS Code](https://code.visualstudio.com/) IDE.

![SQLite Pro Tools Views](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-tools.png?raw=true)

# Features

[SQLite](https://www.sqlite.org/about.html) is an in-process, self-contained, serverless, zero-configuration, transactional SQL database engine. SQLite is an embedded SQL database engine. Unlike most other SQL databases, SQLite does not have a separate server process. SQLite reads and writes directly to ordinary disk files. A complete SQL database with multiple tables, indices, triggers, and views, is contained in a single disk file.

[SQLite Pro Tools](https://github.com/RandomFractals/sqlite-pro-tools) extension adds the following capabilities to VS Code IDE for working with SQLite database files:

- **Connect** to a local [SQLite](https://www.sqlite.org/index.html) database instance
- **Create** new in-memory SQLite database instance
- **View** SQLite databases, tables, views, columns, indexes, modules, settings, and functions in SQL Tools Connections Explorer
- **Run** SQL queries on active SQLite database connections
- **Manage** SQLite database connections in SQL Tools Connections Explorer
- **Auto-complete** SQL keywords, SQLite instance table names, column names, and view names for active SQLite database connections in VS Code SQL editor
- **Save** named SQL query Bookmarks
- **Use** SQL Query History
- **Export** SQLite database query results in `CSV` and `JSON` data formats
- **Use** `SQLite Tools` views and metadata shortcut commands from VS Code `Command Palette...`

See [SQL Tools documentation](https://vscode-sqltools.mteixeira.dev/en/home/) for a comprehensive list of SQL Tools extension features contributed to VS Code IDE.

# Installation

Become a [Pro Sponsor](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=18884) of our new **Pro Data Tools** work on GitHub to access **SQLite Pro Tools**, [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/tree/main#duckdb-pro-tools), [PRQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) and our new [Markdown SQL Pro Tools](https://randomfractals.github.io/pro-data-tools/#markdown-sql-pro-tools) releases and extension `.vsix` installation packages.

All of our GitHub **Pro** sponsors get invited as collaborators to our private [Pro Data Tools](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) repositories, and will be notified about the upcoming updates, new releases, additions, and new [Data Notebook Pro Tools](https://randomfractals.github.io/pro-data-tools/#data-notebook-pro-tools) extension we'll be releasing later this year.

To install **SQLite Pro Tools**, download the latest `sqlite-pro-tools-x.x.x.vsix` from the attached **Assets** in this repository [releases](https://github.com/RandomFractals/sqlite-pro-tools/releases).

Use VS Code IDE [Install from VSIX](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix) feature to install downloaded **SQLite Pro Tools** extension package in VS Code or any other `VSIX`-compatible IDE. **SQLite Pro Tools** work in [VSCodium](https://vscodium.com/) too.

![SQLite Pro Tools VS Code Extension Info](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-tools-extension.png?raw=true)

**Note**: **SQLite Pro Tools** use [Node JS SQLite3 API](https://github.com/TryGhost/node-sqlite3) and require a local [Node.js installation](https://nodejs.org/en/download) to load and query SQLite database files.

Download and install **Node.js** from the official [node.js downloads](https://nodejs.org/en/download) page.

## Table and View Columns

**SQLite Pro Tools** display basic data type icons for text, numeric, and date table and view columns.

![SQLite Table and View Columns](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-table-columns.png?raw=true)

**SQLite Pro Tools** also display primary key column indicators and `not null` column value constraints.

### Indexes

![SQLite Indexes](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-indexes.png?raw=true)

### Modules

![SQLite Modules](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-modules.png?raw=true)

## Configuration Settings

SQLite configuration settings/[compile options](https://duckdb.org/docs/sql/configuration):

![SQLite Settings](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-settings.png?raw=true)

### Functions

![SQLite Functions](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-functions.png?raw=true)

# Commands

**SQLite Pro Tools** provide many standard SQLite database and metadata shortcut commands you can access via `ctrl/cmd+shift+p` shortcut in VS Code or from `View -> Commnad Palette...` menu by typing `SQLite Tools` in the `>` command prompt:

![SQLite Tools Commands](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/sqlite-commands.png?raw=true)

# Demo Data

**SQLite Pro Tools** extension documentation repository contains sample [/data](https://github.com/RandomFractals/sqlite-pro-tools/tree/main/data/chinook/duckdb) folder with the popular [`chinook`](https://github.com/RandomFractals/sqlite-pro-tools/tree/main/data/chinook) database files you can experiment with.

# In-Memory SQLite DB

**SQLite Pro Tools** extension lets you create in-memory database instances by specifying `:memory:` keyword in the Database File field of the new SQLite connection in SQL Tools Connection Assistant. Consult [In-Memory SQLite Databases](https://www.sqlite.org/inmemorydb.html) documentation for more info.

# Configuration

[SQL Tools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) extension provides many configuration [Settings](https://vscode-sqltools.mteixeira.dev/en/settings/) users can toggle to change database connection and tree view display options, sql formatting, and results display.

The following [SQL Tools Settings](https://vscode-sqltools.mteixeira.dev/en/settings/) were used while creating and testing this **SQLite Pro Tools** extension and are recommended for working with DuckDB instances efficiently. We suggest you set these preferences in User Settings in VS Code by navigating to `File -> Preferences -> Settings -> User -> Extensions -> SQLTools`, or adding them to your global VS Code `settings.json` config file using the JSON code snippet below:

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
| ```"sqltools.useNodeRuntime": true``` | Enable Node runtime in order to use [SQLite3 NodeJS API](https://github.com/TryGhost/node-sqlite3) this database SQL tools extension depends on. |
| ```"sqltools.disableNodeDetectNotifications": true``` | Disable Node runtime detection notifications after initial SQLTools extension installation to prevent Node runtime information message display on every new VS Code session start. |
| ```"sqltools.autoOpenSessionFiles": false``` | Prevent auto open of new session SQL editor instance after connecting to the databaase instance. |
| ```"sqltools.results.limit": 10000``` | Maximum number of records to return in results. SQL Tools defaults to displaying only 50 records in query results view. Changing this limit setting to 1000 or 10000 will show more data rows to inspect in result views. |
| ```"sqltools.results.location": "current"``` | Defines the editor group to use for result table views. SQL Tools displays all results in the next editor group to show results on the side next to the active SQL query editor. Changing this setting to `current` will display results in the same editor group and display more result columns. |

# Feedback

Please use our [SQLite Pro Tools Github Discussions](https://github.com/RandomFractals/sqlite-pro-tools/discussions) portal to submit your feedback, share examples of how you are using this VS Code extension, or request new trivial and premium features. Our goal with this extension is to make SQLite more accessible and easier to use in VS Code IDE.

# Support

Become a [Fan or a Pro Sponsor](https://github.com/sponsors/RandomFractals) on GitHub to support our dev work on **SQLite Pro Tools**, new [**Pro Data Tools**](https://github.com/RandomFractals/pro-data-tools/tree/main#pro-data-tools) and other free and public [Random Fractals, Inc. code and data viz extensions](https://marketplace.visualstudio.com/publishers/RandomFractalsInc).

Help us reach our goal of getting at least 10 **Pro** sponsors on GitHub. 🙏

💖 https://github.com/sponsors/RandomFractals
