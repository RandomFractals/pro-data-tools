# Changelog

Combined [Pro Data Tools](https://github.com/RandomFractals/pro-data-tools#pro-data-tools) changelog for all the VS Code extensions and versions released to our [Pro sponsors](https://github.com/sponsors/RandomFractals) on GitHub.

## Markdown SQL Pro Tools v1.2.0 (2023-08-03)

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

## Markdown SQL Pro Tools v1.1.0 (2023-07-07)

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

## Markdown SQL Pro Tools v1.0.0 (2023-06-20)

- Scaffold `Markdown Sql Pro Tools` extension code base from PRQL Code Lens in PRQL Pro Tools VS Code extension
- Create custom Markdown SQL Pro Tools extension icon
- Enhance SQL Code Lens provider and SQL Tools extension plugin to support SQL code blocks in markdown documents
- Create Markdown Sql code selection command
- Add `Execute SQL statement(s)` code lens to the SQL code blocks in markdown documents
- Document, package, and release Markdown SQL Pro Tools v1.0.0
