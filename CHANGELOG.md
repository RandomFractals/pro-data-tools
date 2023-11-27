# Changelog

Combined [Pro Data Tools](https://github.com/RandomFractals/pro-data-tools#pro-data-tools) changelog for all the VS Code extensions and versions released to our [Pro sponsors](https://github.com/sponsors/RandomFractals) on GitHub.

## SQLite Pro Tools v1.0.0 - [2023-11-27]

- Create new SQLite Tools VS Code extension codebase from SQL Tools and drivers monorepo
- Update SQLite3 Node JS library to the latest v5.1.6 version
- Create custom SQLite Pro Tools extension and database connection display icons
- Add column data type icons display for tables and views in SQL Tools Connection Explorer
- Display SQLite database Indexes in SQL Tools Connection Explorer
- Display SQLite Modules in SQL Tools Connection Explorer
- Add Random Fractals Inc. license file
- Replace Tables and Views folder icons with built-in VS Code windows and layers icons in SQL Tools Connection Explorer
- Add SQLite Settings/Compile Options display to SQL Tools Connection Explorer
- Create `/data` folder with demo SQLite database to use for testing
- Create `SQLite Tools:` shortcut commands to list all databases, tables, views, indexes, foreign keys, triggers, configuration options, etc.
- Refine SQLite database schema queries in `queries.ts`
- Add Car Company demo database for testing
- Add `SQLite Tools: View DB Stats` shortcut command
- Display index table and column name in `View All Indexes` SQLite Tools command and SQL query
- Add `SQLite Tools: View All Functions` shortcut command
- Add `SQLite Tools: View Module List` shortcut command
- Add `SQLite Tools: View Pragma List` shortcut command
- Display SQLite Functions list in SQL Tools Connection Explorer tree view
- Document SQLite Pro Tools features, views, configuration settings, installation, demo data and commands in `README.md`
- Create SQLite Pro Tools `CHANGELOG.md` for the first private beta version extension package release
- Package and publish new SQLite Pro Tools extension

## DuckDB SQL Tools v1.3.0 - [2023-10-27]

- Update DuckDB SQL Tools and demo DuckDB configs to use new DuckDB v0.9.1 NodeJS libraries
- Update DuckDB SQL Tools `chinook-duckdb.ipynb` and generated demo `chinook.duckdb` to use DuckDB v0.9.1
- Update DuckDB SQL Tools documentation with new DuckDB v0.9.1 support info
- Package and publish DuckDB SQL Tools v1.3.0 with DuckDB v0.9.1 support

## PRQL Pro Tools v1.3.0 - [2023-10-14]

- Update PRQL JS library to v0.9.5
- Update PRQL query examples to work with `prql-js` v0.9.5
- Package and publish PRQL Pro Tools v1.3.0 release

## DuckDB SQL Tools v1.2.0 - [2023-10-06]

- Update free public DuckDB SQL Tools Preview extension to support DuckDB v0.8.1
- Update SQL Tools drivers link and screenshot in docs
- Add DuckDB Pro Tools View Commands demo gif to DuckDB SQL Tools documentation
- Update PRQL Pro Tools links in DuckDB SQL Tools documentation
- Update new Markdown SQL Pro Tools info in DuckDB SQL Tools documentation
- Add new Data Notebook Pro Tools info to DuckDB SQL Tools documentation
- Update Random Fractals Data Tools and new Pro Data Tools sections in DuckDB SQL Tools documentation
- Package and publish DuckDB SQL Tools v1.2.0 release with DuckDB v0.8.1 support

## Markdown SQL Pro Tools v1.3.0 - [2023-08-14]

- Skip adding top level `Select All`, `Extract All`, and `Bookmark All` SQL code lenses to open markdown documents without SQL code blocks

## Markdown SQL Pro Tools v1.2.0 - [2023-08-03]

- Support SQL magics (`%%sql`) in markdown SQL code fences and parsing of SQL code blocks for SQL code lenses
- Add SQL code lenses to SQL code blocks and string literals in Observable markdown (`.omd`) and Observable JS (`.ojs`) documents
- Add SQL code lenses to SQL code blocks and cells with SQL magics in `.qmd` Quarto markdown documents
- Add SQL code lenses to SQL code blocks in `.Rmd` markdown documents
- Add new top level `Extract All` SQL code lens to markdown documents
- Add SQL code lenses to single line SQL magic with `%sql` and `select` statements
- Add new top level `Select All` SQL code lens to the supported `.*md` markdown documents with SQL code blocks
- Skip SQL code blocks with only `--` comment lines and no SQL statements when adding SQL code lenses to open SQL document
- Highlight SQL code blocks in markdown document using SQL Tools query code decorator styles
- Create Observable DuckDB Data Tables example with SQL string literals to demo SQL code lenses in Observable JS, markdown and Quarto markdown documents
- Refactor SQL code blocks and string literals extraction and SQL code lenses construction for supported documents
- Add new top level `Bookmark All` SQL code lens to markdown documents
- Document, package and publish Markdown SQL Pro Tools v1.2.0 release

## Markdown SQL Pro Tools v1.1.0 - [2023-07-07]

- Rename `Execute SQL statement(s)` code lens title to `Execute`
- Rename `Execute All SQL statement(s)` code lens title to `Execute All`
- Use `notebook-execute-all` and `notebook-execute` VS Code icons for the `Execute All` and `Execute` SQL code lens icons
- Don't add top-level `Execute All` SQL statement(s) code lens when no SQL code blocks are detected in the open `.md` markdown document
- Add `Execute`, `Select`, `Copy`, and `Create` SQL code lenses to individual SQL statements in standard `.sql` documents
- Add `Copy` SQL to Clipboard code lens to SQL code blocks in `.md` markdown documents
- Add `Create` SQL code lens to SQL code blocks in `.md` markdown documents to open selected SQL code in a new virtual SQL document VS Code editor
- Rename `Select SQL code` code lens title to `Select` with `Select SQL code ...` in the code lens tooltip
- Use `Markdown SQL Tools` category for all custom SQL code lens commands
- Refactor SQL code lenses provider and SQL code blocks matching for markdown documents
- Add new `Features` section to `README.md`
- Add new `Copy` SQL to clipboard and `Create` new SQL document code lenses info and example to `README.md`
- Update VS Code SQL and Data Tools sections in `README.md`
- Update Markdown SQL Pro Tools section in new public `pro-data-tools` documentation repository
- Update `Data Notebook` extension info and demo gifs in `README.md`
- Create new Markdow SQL Pro Tools demo gif and update extension intro section in `README.md`
- Package and publish Markdown SQL Pro Tools v1.1.0 release

## DuckDB Pro Tools v1.4.0 - [2023-06-27]

DuckDB Pro Tools v1.4.0 updates DuckDB NodeJS libraries, create demo DuckDB Jupyter notebooks, and demo `.duckdb` files in the `/data` folder to [DuckDB v0.8.1](https://github.com/duckdb/duckdb/releases/tag/v0.8.1).

- Update DuckDB Pro Tools to use DuckDB v0.8.1 NodeJS libraries
- Update all `.duckdb` files and create DuckDB Jupyter notebooks in DuckDB Pro Tools `/data` folder to use DuckDB v0.8.1
- Add DuckDB version info and detailed error logging to DuckDB Pro Tools connection error message display
- Update DuckDB Pro Tools `README.md` with DuckDB v0.8.1 support info
- Add VS Code SQL and Data Tools sections to DuckDB Pro Tools `README.md`
- Package and publish DuckDB Pro Tools v1.4.0 with DuckDB v0.8.1 support

## DuckDB SQL Tools v1.1.0 - [2023-06-26]

- Update DuckDB Sql Tools extension to use DuckDB v0.7.1
- Update DuckDB Sql Tools demo `chinook.duckdb` file to use DuckDB v0.7.1 storage format
- Add DuckDB version info, detailed error logging, and DuckDB Pro Tools info to the DuckDB Sql Tools driver and DuckDB connection error message display
- Update DuckDB SQL Tools `README.md` with new DuckDB v0.7.1 support info
- Add VS Code SQL and Pro Data Tools info to the public DuckDB Sql Tools extension `README.md`
- Package and publish DuckDB SQL Tools v1.1.0 with DuckDB v0.7.1 support

## PRQL Pro Tools v1.2.0 - [2023-06-23]

- Update PRQL Pro Tools to use `prql-js` v0.8.1, DuckDB Pro Tools v1.3.0, and DuckDB v0.8.0

## DuckDB Pro Tools v1.3.0 - [2023-06-22]

DuckDB Pro Tools v1.3.0 updates DuckDB NodeJS libraries, create demo DuckDB Jupyter notebooks, and demo `.duckdb` files in the `/data` folder to [DuckDB v0.8.0](https://github.com/duckdb/duckdb/releases/tag/v0.8.0).

- Update DuckDB Pro Tools to use DuckDB v0.8.0 NodeJS libraries
- Update all `.duckdb` files and create DuckDB Jupyter notebooks in DuckDB Pro Tools `/data` folder to use DuckDB v0.8.0
- Update DuckDB Pro Tools `README.md` with DuckDB v0.8.0 support info
- Package and publish DuckDB Pro Tools v1.3.0 with DuckDB v0.8.0 support

## Markdown SQL Pro Tools v1.0.0 - [2023-06-20]

- Scaffold `Markdown Sql Pro Tools` extension code base from PRQL Code Lens in PRQL Pro Tools VS Code extension
- Create custom Markdown SQL Pro Tools extension icon
- Enhance SQL Code Lens provider and SQL Tools extension plugin to support SQL code blocks in markdown documents
- Create Markdown Sql code selection command
- Add `Execute SQL statement(s)` code lens to the SQL code blocks in markdown documents
- Document, package, and release Markdown SQL Pro Tools v1.0.0

## DuckDB Pro Tools v1.2.0 - [2023-05-17]

DuckDB Pro Tools v1.2.0 adds over 30 new DuckDB views and metadata shortcut commands to the VSCode Command Palette under `DuckDB Tools` commands category, and features new `prompt.sql` query examples created with the free [Hugging Face Code Autocomplete](https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode) extension.

- Add DuckDB metadata functions shortcut commands to DuckDB Pro Tools
- Move DuckDBDatabase namespace and interfaces to new duckdb.ts
- Move DuckDBPro tools driver name and extension id/name constants to constants.ts
- Add AI generated query examples for the employees database demo data in DuckDB Pro Tools
- Package and publish DuckDB Pro Tools v1.2.0 release

## DuckDB Pro Tools v1.1.0 - [2023-05-01]

DuckdDB Pro Tools v1.1.0 release with extended DB objects tree view display, improved SQL intellisense, and alpha implementation of read/write DB access mode and connections handling.

- Create Enhanced DB tree view with more DB objects for the DuckDB Pro Tools extension
- Add more chinook demo db sql queries to run in a data notebook
- Open DuckDBPro instances in read write access mode by default
- Add DuckDB Pro Tools v1.1.0 images and feature demo gifs to the public DuckDB Sql Tools repository
- Document and publish DuckDB Pro Tools v1.1.0 with extended DuckDB instance tree view objects and results display

## DuckDB Pro Tools v1.0.3 - [2023-03-23]

First private DuckDB Pro Tools beta release.

- Add more info about database storage and versions to DuckDB Storage section in docs
- Create new Employees DuckDB with parquet files to run PRQL queries
- Add PRQL and SQL query examples from PRQL book
- Create new duckdb-pro-tools extension package
- Add Run PRQL on active DuckDB connection to DuckDB Pro Tools extension
- Updated chinook.duckdb SQL queries generated from PRQL to use the latest PRQL library version (0.5.0)
- Move atrist-track-prices.prql and generated sql to data/chinook/sqlite data and queries folder
- Link DuckDB Sql Tools home page to public preview/docs repo
- Use new PRQL extension settings in this project config
- Update chinook.duckdb demo data to DuckDB v0.7.1 storage format in DuckDB Pro Tools extension package
- Use duckdb.js library v0.7.1 in the Pro version of DuckDB Tools
- Move new PRQL Run Query Code Lens to new PRQL Tools repository
- Remove PRQL Code Lens code from DuckDB Pro Tools extension
- Set DuckDB Pro SQLTools driver name to DuckDB Pro
- Add employees.duckdb config to workspace settings using new DuckDBPro driver to test it
- Add a black dot to the DuckDB Pro extension and DB state icons
- Add TPC-DS /data folder with DuckDB schema SQL script, load data SQL, and TPC-DS SQL queries and data
- Rename TPC-DS load.sql to load-csv.sql and add load-parquet.sql script
- Add /gbif data folder with sample SQL and PRQL queries for AWS hosted public datasets
- Update all create DuckDB notebooks and .duckdb files in /data folder to use DuckDB v0.7.1 storage format
- Create DuckDB SVG icons for the DuckDB Pro Tools version
- Create new DuckDB Pro Tools documentation
- Use new DuckDB Pro svg icons for conenctions display instead of png
- Move Chicago crimes create table and query examples to new data/chicago-crimes folder
- Add new chicago-crimes.duckdb in-memory db pro config to data folder
- Change GBIF demo duckdb config to DuckDBPro instance
- Rename GBIF data/sql folder to data/gbif-observations
- Cleanup DuckDB and DuckDBPro db configs for DuckDBPro Tools release
- Install and load DuckDB JSON extension for all open DuckDB connections
- Add remote JSON data loading examples
- Remove the old playlists demo data and config
- Add DuckDB Pro Tools docs/images and demo gifs
- Create tpc-h-duckdb-gen.ipynb Jupyter notebook and test DuckDB Pro Tools with TPC-H 1, 10, and 100 DB scale factors
- Add Chicago Traffic Estimates Jupyter notebook and Restbook to test DuckDB HTTPFS and JSON data loading from URL with redirects
- Add DuckDB Pro Tools images to the public DuckDB Sql Tools repository for images to load on Extension Info page in VSCode

## PRQL Pro Tools v1.1.0 - [2023-03-15]

- Update `prql-js` to v0.6.1 to execute PRQL loops and use other new PRQL language and compiler features
- Add GBIF sample PRQL query run gif to docs

## PRQL Pro Tools v1.0.0 - [2023-03-03]

- Move new PRQL Run Query Code Lens from DuckDB Tools monorepo to this new PRQL Tools monorepo
- Create custom PRQL Run extension icons for PRQL Tools
- Document PRQL Code Lens extension package
- Package and publish the first PRQL Code Lens extension private beta v. release
- Add `/data` folder with our `chinook.duckdb` instance from DuckDB Sql Tools for testing and sample runs
- Create new /scripts/prql folder with .prql files for testing and sample PRQL Query runs
- Add PRQL vscode extension dependency for PRQL documents grammar support
- Use prql.target setting to get SQL for the PRQL Run Query code lens
- Create PRQL Pro Tools README.md with a summary of PRQL Pro Tools extension pack

## DuckDB SQL Tools v1.0.2 - [2023-01-28]

Documentation Update Release.

- Refine DuckDB SQL Tools extension intro, features list, and other doc sections in README.md

## DuckDB SQL Tools v1.0.1 - [2023-01-27]

Minor extension packaging update for the extension gallery banner background color display in VSCode marketplace.

- Add gallery banner color to extension package manifest

## DuckDB SQL Tools v1.0.0 - [2023-01-27]

Initial Public Preview Release.

- Create DuckDB tools monorepo structure
- Create duckdb-sql-tools vscode extension package
- Create DuckDB Sql Tools driver base code
- Create DuckDB sql tools icons
- Add DuckDB SQL tools demo gif for docs
- Create DuckDB sql tools driver using NodeJS libraries
- Add PRQL query examples for the demo db and data files in data folder
- Add chinook demo db data files in different formats
- Create DuckDB SQL Tools preview version README.md
- Add Random Fractals Inc. license file
- Allow to create readwrite `:memory:` database connections
- Add httpfs data loading example
- Add sample duckdb sql query examples
- Add better chinook db create sql script with primary keys and indexes
- Add chinook duckdb Jupyter notebook and create new chinook.duckdb file using duckdb v0.6.1
- Add VSCode Memory Limit info to Limitations section in vscode extension README.md
- Add additional DuckDB keywords, pragmas, and metadata functions to SQL keywords
- Add demo data section to vscode extension README.md
- Create CHANGELOG.md for the DuckDB SQL Tools extension v1.0.0 release
- Package and publish DuckDB Sql Tools v1.0.0 Preview release
