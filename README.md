# Random Fractals Inc. Data Tools

[Random Fractals](https://twitter.com/search?q=(%23RandomFractalsInc)%20(from%3ATarasNovak)&src=typed_query&f=top) Inc. [**Data Tools**](https://twitter.com/search?q=(%23DataTools)%20(from%3ATarasNovak)&src=typed_query) 🛠️ is a collection of public [data visualization extensions](https://marketplace.visualstudio.com/search?term=dataViz&target=VSCode&category=All%20categories&sortBy=Relevance), [data viewers](https://marketplace.visualstudio.com/search?term=data%20viewer&target=VSCode&category=All%20categories&sortBy=Relevance), VS Code [Notebook renderers](https://marketplace.visualstudio.com/search?term=notebook%20renderer&target=VSCode&category=All%20categories&sortBy=Relevance), and [code snippets](https://marketplace.visualstudio.com/search?term=Random%20Fractals%20code%20snippets&target=VSCode&category=All%20categories&sortBy=Relevance) for devs and data scientists using VS Code IDE, published under our [Random Fractals Inc.](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) ☂️ org.

![Random Fractals Data Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/random-fractals-data-tools.png?raw=true)

# Pro Data Tools

**Pro Data Tools** is a new Premium set of SQL and [PRQL](https://prql-lang.org/) Code Lenses and Data Viewers created for our monthly [**Pro sponsors**](https://github.com/sponsors/RandomFractals/sponsorships?sponsor=RandomFractals&tier_id=18884) on GitHub to enhance SQL development and SQL statements execution runtime workflow in VS Code IDE, connected to the different database management systems via [SQL Tools extension](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools), database plugins, and [SQL Tools drivers](https://marketplace.visualstudio.com/search?term=tag%3Asqltools-driver&target=VSCode&category=All%20categories&sortBy=PublishedDate).

![Pro Data Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/pro-data-tools.png?raw=true)

## DuckDB Pro Tools

Our [**Pro Data Tools**](https://www.linkedin.com/feed/hashtag/?keywords=prodatatools) 🛠️ include [DuckDB Pro Tools](https://www.linkedin.com/feed/hashtag/?keywords=duckdbprotools) extension that adds advanced [DuckDB](https://duckdb.org/) connection features and support to VSCode IDE, and provides database schemas display, DuckDB extensions and settings views, information schema and catalog views, SQL query API and user interfaces integrated with the popular SQL Tools extension, SQL query editor, SQL language server, and VS Code data processing tools.

![DuckDB Pro Tools Views](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/duckdb-pro-tools-views.gif?raw=true)

You can read more about the free and public [DuckDB SQL Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-sql-tools) *Preview* VS Code extension and new Premium [DuckDB Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) extension capabilites and features on our new [DuckDB Tools](https://randomfractals.github.io/pro-data-tools/duckdb-tools) documentation page.

## PRQL Pro Tools

Our [**Pro sponsors**](https://github.com/sponsors/RandomFractals/sponsorships?sponsor=RandomFractals&tier_id=18884) on GitHub also get access to the Premium [PRQL Pro Tools](https://www.linkedin.com/feed/hashtag/?keywords=prqlprotools) VS Code extension. **PRQL Pro Tools** extension comes with a custom [PRQL Code Lens](https://www.linkedin.com/feed/hashtag/?keywords=prqlcodelens) SQL Tools plugin that allows you to run [PRQL](https://prql-lang.org/) queries for the supported PRQL target [SQL dialects](https://prql-lang.org/book/project/target.html#dialects) **directly** using any of the supported SQL Tools extension drivers for the different database management systems.

![PRQL Pro Tools Code Lens](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/prql-code-lens-pro-tools.gif?raw=true)

## Markdown SQL Pro Tools

**Markdown SQL Pro Tools** extension adds custom SQL [Code Lenses](https://code.visualstudio.com/api/language-extensions/programmatic-language-features#codelens-show-actionable-context-information-within-source-code) to SQL code blocks in standard SQL and various markdown documents in VS Code IDE.

The provided **SQL Code Lenses** include top-level SQL and markdown document `Execute All`, `Select All`, `Extract All`, `Bookmark All` SQL code lenses, `Execute`, `Select`, and `Copy` SQL code block lenses, and `Create` New SQL document from SQL code block lens.

 Our **SQL Code Lenses** integrate with the popular [SQL Tools](https://vscode-sqltools.mteixeira.dev/en/home/) Connections manager, supported [SQL Tools drivers](https://marketplace.visualstudio.com/search?term=tag%3Asqltools-driver&target=VSCode&category=All%20categories&sortBy=PublishedDate), and query results viewer to execute SQL **directly** on any of the supported SQL Tools database management systems and view results.

![Markdown SQL Pro Tools](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-pro-tools-v1.1.0.gif?raw=true)

## Markdown SQL Features

**Markdown SQL Pro Tools** add the following top-level **SQL Code Lenses** to SQL and markdown documents open in VS Code IDE:

- `Execute All` SQL code lens to execute all SQL statements in the open SQL or markdown document
- `Select All` SQL code lens to select all SQL code blocks in the open markdown document
- `Extract All` SQL code lens to extract all SQL code blocks from the open markdown document
- `Bookmark All` SQL code lens to bookmark all SQL code blocks in the open markdown document

This extension also adds the following SQL Code Lenses to individual SQL code blocks in the open markdown documents and SQL statements in SQL documents:

- `Execute` SQL code lens to run SQL code using active SQL Tools database connection
- `Select` SQL code lens to select SQL code block in the open SQL or markdown document editor
- `Copy` SQL code lens to copy SQL code block to the clipboard
- `Create` SQL code lens to create new SQL document from SQL code block in the open text editor

### Supported Markdown Documents and SQL Highlights

**Markdown SQL Pro Tools** detect and highlight SQL code blocks in stanadard `.md` markdown documents, `.Rmd` [R markdown](https://rmarkdown.rstudio.com/) documents, `.qmd` [Quarto](https://quarto.org/) publishing documents, `.ojs` and `.omd` [Observable JS](https://marketplace.visualstudio.com/items?itemName=GordonSmith.observable-js) and markdown documents.

The supported SQL code blocks include [code fences](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks) with `sql` tag, `%%sql` magic code blocks, and `%sql` magic code lines with `SELECT` statements.

![Markdown SQL Code Highlights](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-code-highlight.png?raw=true)

You can use new top-level `Select All` SQL code lens to select all detected SQL code blocks in the open markdown document.

![Markdown SQL Code Selections](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-selections.png?raw=true)

### Markdown SQL Code Bookmarks

Users of the popular [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) VS Code extension can use new top-level `Bookmark All` SQL code lens to toggle SQL code bookmarks in the open markdown documents.

![Markdown SQL Code Bookmarks](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-bookmarks.png?raw=true)

Using **Markdown SQL Pro Tools** with new **SQL Bookmarks**, SQLite and our **DuckDB Pro** SQL Tools in VS Code IDE on [Ploomber's JupySQL](https://github.com/ploomber/jupysql/blob/master/doc/quick-start.md) Jupyter book markdown docs:

![Using Markdown SQL Code Bookmarks](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-bookmarks.gif?raw=true)

**Note**: Install [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) extension separately to see new `Bookmark All` SQL code lens enabled in the supported markdown documents.

### Interactive SQL in Quarto Docs

The **Markdown SQL Pro Tools** v1.2.0 and above add **SQL Code Lenses** to SQL code blocks in [Quarto](https://quarto.org/) markdown docs in VS Code IDE.

Quick demo of setting up local HR SQLite database with SQL Tools VS Code extension, rendering Quarto markdown document with [Quarto](https://marketplace.visualstudio.com/items?itemName=quarto.quarto) extension, and using our new SQL code lenses to Execute SQL queries from standard `.md` and `.qmd` markdown documents code:

![Interactive SQL in Quarto Docs](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-in-quarto.gif?raw=true)

You can install and use [Interactive SQL](https://github.com/shafayetShafee/interactive-sql) Quarto extension to experiment with it in VS Code with Quarto markdown docs.

### Interactive SQL in R Markdown

You can also use new **SQL Code Lenses** in [R Markdown](https://rmarkdown.rstudio.com/) documents in VS Code IDE.

[SQL in RMD](https://github.com/sciencificity/sql-in-rmd/tree/main) GitHub repository provides a great example of using SQL code chunks in R markdown documents.

Setting up demo SQLite database connection and using our **SQL Code Lenses** to run SQL queries from R markdown document:

![Interactive SQL in R Markdown](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-in-rmd.gif?raw=true)

## Markdown SQL Feature Contributions

**Markdown SQL Pro Tools** contribute the following Commands and Activation Events to VS Code IDE for working with SQL code in markdown and SQL documents.

![Markdown SQL Pro Tools Feature Contributions](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/markdown-sql-pro-tools-contributions.png?raw=true)

**Markdodown SQL Pro Tools** extension is available under the new [**Markdown Sql Pro Tools**](https://github.com/sponsors/RandomFractals/sponsorships?sponsor=RandomFractals&tier_id=295482) monthly sponsor subscription on GitHub and also includes access to the [**DuckDB Pro**](https://randomfractals.github.io/pro-data-tools/#duckdb-pro-tools) SQL Tools plugin and [**PRQL Code Lens**](https://randomfractals.github.io/pro-data-tools/#prql-pro-tools) extension from our Premium [**Pro Data Tools**](https://randomfractals.github.io/pro-data-tools/#pro-data-tools) extensions pack.

## Data Notebook Pro Tools

The new [**Data Notebook Pro Tools**](https://twitter.com/search?q=(%23DataNotebooks)%20(from%3ATarasNovak)&src=typed_query) extension from our Premium **Pro Data Tools** extensions pack will be released later this year for our [**Pro sponsors**](https://github.com/sponsors/RandomFractals) on GitHub.

**Data Notebook Pro** extension integrates SQL Tools connections, supported database management systems, our [**Data Table Renderers**](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.vscode-data-table) and VS Code Jupyter Notebook user interface to view and run SQL queries from `.sql` files and `.md` markdown documents with SQL code blocks using native VS Code Notebook View.

![Data Notebook Extension](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/data-notebook-extension.png?raw=true)

### Data Notebook SQL Query

Simple example of running SQL query with the new **Data Notebook Pro Tools** extension:

![Data Notebook SQL Query](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/data-notebook-sql-query.gif?raw=true)

### Data Notebook Output Rendering

Using different [**Data Table Renderers**](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.vscode-data-table) in the **Data Notebook** created from SQL document with multiple SQL queries:

![Data Notebook Output Rendering](https://github.com/RandomFractals/pro-data-tools/blob/main/docs/images/data-notebook-output-rendering.gif?raw=true)

## Future Pro Data Tools Releases

We plan to publish new **Pro Data Tools** updates and releases monthly. The best way to keep up to date on the new features and enhancements added to **DuckDB Pro Tools** extension, [PRQL Pro Tools](https://github.com/RandomFractals/prql-pro-tools), recently released [Markdown SQL Pro Tools](https://twitter.com/hashtag/MarkdownSQLProTools?src=hashtag_click), and the upcoming [Data Notebook Pro](https://twitter.com/search?f=live&q=(%23DataNotebook)%20(from%3ATarasNovak)&src=typed_query) extension is to follow us on X/Twitter [@TarasNovak](https://twitter.com/TarasNovak), or follow [Data Samurai](https://vis.social/@dataSamurai) on Vis Social Mastodon. We share new [Pro Data Tools](https://twitter.com/search?f=live&q=(data%20OR%20pro%20OR%20tools)%20(from%3ATarasNovak)&src=typed_query) related demos and content there almost daily.

![Taras Novak on Twitter](https://github.com/RandomFractals/duckdb-sql-tools/blob/main/docs/images/taras-novak-twitter.png?raw=true)

## Pro Data Tools Changelog

We created new combined **Pro Data Tools** [changelog](https://randomfractals.github.io/pro-data-tools/CHANGELOG) to capture all the premium VS Code extensions and versions with detailed features list released to our [Pro sponsors](https://github.com/sponsors/RandomFractals/sponsorships?tier_id=295482) on GitHub this year.

📜 [https://github.com/RandomFractals/pro-data-tools/blob/main/CHANGELOG.md](https://github.com/RandomFractals/pro-data-tools/blob/main/CHANGELOG.md)

# Feedback

Please use our new [Pro Data Tools GitHub Discussions](https://github.com/RandomFractals/pro-data-tools/discussions) portal to submit your feedback, share examples of how you are using our public VS Code [data viz extensions](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) and new **Pro Data Tools**, or request new trivial and premium features. Our goal with these generic Data Tools 🛠️ and SQL Tools extensions is to make local and remote data more accessible and easier to use and visualize for all the devs and data scientists out there using VS Code IDE, VSCodium and Azure Data Studio.

# Support

Become a [Fan or a Pro Sponsor](https://github.com/sponsors/RandomFractals) on GitHub to support our dev work on these Data Tools and other [Random Fractals, Inc. code and data viz extensions](https://marketplace.visualstudio.com/publishers/RandomFractalsInc) if you find them useful, educational, or enhancing your daily dataViz dev code workflows and exploratory data analysis experience.

💖 [https://github.com/sponsors/RandomFractals](https://github.com/sponsors/RandomFractals)
