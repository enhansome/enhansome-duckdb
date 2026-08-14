<!--lint disable awesome-git-repo-age-->

# Awesome DuckDB with stars

> A curated list of awesome DuckDB libraries, tools and resources.

[DuckDB](https://duckdb.org/) is an analytical in-process SQL database management system.

The Quack client-server protocol was released on 2026-05-12: see the [Quack page](https://duckdb.org/quack/).

DuckDB 1.5.0 was released on 2026-03-09: see the [announcement blog post](https://duckdb.org/2026/03/09/announcing-duckdb-150).

The DuckLake file format was released on 2025-05-27: see the [website](https://ducklake.select/).

<!-- omit in toc -->

## Contents

* [Resources](#resources)
* [Installers](#installers)
* [Newsletters](#newsletters)
* [Logos and Icons](#logos-and-icons)
* [Client APIs](#client-apis)
* [Tools Powered by DuckDB](#tools-powered-by-duckdb)
* [Backends](#backends)
* [Libraries Powered by DuckDB](#libraries-powered-by-duckdb)
* [DuckDB Clients and UIs](#duckdb-clients-and-uis)
  * [Web Clients (WebAssembly)](#web-clients-webassembly)
* [SQL Clients and IDE that Support DuckDB](#sql-clients-and-ide-that-support-duckdb)
* [Projects Powered by DuckDB](#projects-powered-by-duckdb)
* [Integrations](#integrations)
* [Client-Server Setups](#client-server-setups)
* [Extensions](#extensions)
  * [Core Extensions](#core-extensions)
  * [Community Extensions](#community-extensions)
  * [Other Extensions](#other-extensions)
  * [Extension Statistics](#extension-statistics)
* [Tutorials](#tutorials)
* [Media](#media)
  * [Talks](#talks)
  * [Podcasts](#podcasts)
  * [Blog Posts](#blog-posts)
  * [Books](#books)
* [Contribute](#contribute)

## Resources

* [Serverless DuckDB as API](https://github.com/tobilg/serverless-duckdb) ⭐ 226 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - Use DuckDB as API with Amazon API Gateway and AWS Lambda.
* [Serverless DuckDB over S3](https://github.com/BauplanLabs/quack-reduce/) ⭐ 223 | 🐛 4 | 🌐 Python | 📅 2024-01-10 - Running DuckDB over a data lake on S3 using lambda.
* [DuckERD CLI](https://github.com/tobilg/duckerd) ⭐ 157 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-06 – A CLI tool to create an ER Diagram from DuckDB database files.
* [DuckDB AWS Lambda layer (Node.js)](https://github.com/tobilg/duckdb-nodejs-layer) ⭐ 153 | 🐛 1 | 🌐 Python | 📅 2026-01-31 - Run DuckDB in AWS Lambda functions.
* [Awesome DuckLake](https://github.com/esadek/awesome-ducklake) ⭐ 141 | 🐛 5 | 📅 2026-04-20 - A curated list of awesome DuckLake tools and resources.
* [Serverless Parquet Repartitioner](https://github.com/tobilg/serverless-parquet-repartitioner) ⭐ 41 | 🐛 0 | 🌐 JavaScript | 📅 2025-03-30 - Use DuckDB to repartition data in S3-based Data Lakes.
* [duckdb-docker](https://github.com/duckdb/duckdb-docker) ⭐ 21 | 🐛 3 | 🌐 Shell | 📅 2026-01-02 - Official Docker image for the DuckDB CLI.
* [DuckDB AWS Lambda layer (Python)](https://github.com/bengeois/aws-layer-duckdb-python) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-08-03 - Run DuckDB in AWS Lambda functions using Python.
* [duckdb-nf](https://github.com/edmundmiller/duckdb-nf) ⭐ 3 | 🐛 0 | 🌐 Nextflow | 📅 2025-03-27 - Example uses of DuckDB with Nextflow.
* [Official documentation](https://duckdb.org/docs/) - Official DuckDB documentation.
  * [Official blog](https://duckdb.org/news/) - Official DuckDB blog.
  * [DuckDB RSS feed](https://duckdb.org/feed.xml) - Feed for the official DuckDB blog.
  * [DuckDB clients](https://duckdb.org/docs/clients/overview) - Client APIs for DuckDB.
  * [DuckDB documentation PDF](https://blobs.duckdb.org/docs/duckdb-docs.pdf) - The DuckDB documentation as a single PDF file.
  * [DuckDB documentation MD](https://blobs.duckdb.org/docs/duckdb-docs.md) - The DuckDB documentation as a single Markdown file.
* [DuckLake](https://ducklake.select/) - A lakehouse format from the team behind DuckDB.
* [DuckDB setup](https://github.com/marketplace/actions/duckdb-setup) - GitHub Action to install DuckDB in CI.
* [DuckDB snippets](https://duckdbsnippets.com/) - Collection of snippets curated by MotherDuck.
* [DuckDB tldr page](https://tldr.inbrowser.app/pages/common/duckdb) - DuckDB's entry in [tldr pages](https://tldr.sh/), available in CLI via the `tldr duckdb` command.
* [Compatible DuckDB extensions for AWS Lambda](https://extensions.quacking.cloud/) - Extensions specifically compiled for the AWS Lambda runtime (GLIBC 2.26).
* [Observable notebooks](https://observablehq.com/search?query=duckdb\&sort=created\&direction=desc\&useES=true) - Notebooks using DuckDB on the Observable data visualization platform.
* [SQLNotebook](https://www.timestored.com/sqlnotebook/) - SQL notebooks by TimerStored powered by DuckDB.
* [DuckDB execution plan visualizer](https://db.cs.uni-tuebingen.de/explain/) - Visualizing and understanding DuckDB EXPLAIN plans made easy.
* [DuckDB in Science](https://duckdb.org/science/) - A collection of scientific papers building on DuckDB.

## Installers

* [Official installation page](https://duckdb.org/docs/installation/)
* [Brew formula](https://formulae.brew.sh/formula/duckdb)
* Third-party installation options. Note: these are not maintained by the core DuckDB team – proceed with caution.
  * [DuckDB version manager (`duckman`)](https://github.com/NiclasHaderer/duckdb-version-manager) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2026-07-22 – Cross-platform installer and version manager for DuckDB.
  * [Snap package](https://github.com/habedi/duckdb-snap) ⚠️ Archived - Snap package of DuckDB, e.g., for Ubuntu Linux.
  * [Chocolatey packages](https://community.chocolatey.org/packages/duckdb) - Chocolatey package for Windows.

## Newsletters

* [DuckDB Newsletter](https://motherduck.com/duckdb-news/) - Monthly newsletter by MotherDuck.
* [Learn DuckDB by example](https://learningduckdb.com/) - Newsletter by Tobias Müller.

## Logos and Icons

* [Logos](https://duckdb.org/faq#where-do-i-find-the-duckdb-logo) - DuckDB logos.
* [Iconify](https://icon-sets.iconify.design/simple-icons/duckdb/) - Monochrome DuckDB icon in Iconify.

## Client APIs

* [Rust](https://github.com/duckdb/duckdb-rs) ⭐ 951 | 🐛 21 | 🌐 Rust | 📅 2026-08-10
* [.NET](https://github.com/Giorgi/DuckDB.NET/) ⭐ 695 | 🐛 24 | 🌐 C# | 📅 2026-08-14
* [Go](https://github.com/duckdb/duckdb-go) ⭐ 284 | 🐛 50 | 🌐 Go | 📅 2026-08-12
* [Ruby](https://github.com/suketa/ruby-duckdb) ⭐ 255 | 🐛 12 | 🌐 Ruby | 📅 2026-08-14
* [PHP](https://github.com/satur-io/duckdb-php) ⭐ 87 | 🐛 15 | 🌐 C | 📅 2026-04-02
* [Dart](https://github.com/TigerEyeLabs/duckdb-dart) ⭐ 72 | 🐛 9 | 🌐 Dart | 📅 2025-11-24
* [PowerShell](https://github.com/dfinke/PSDuckDB) ⭐ 61 | 🐛 2 | 🌐 PowerShell | 📅 2024-09-10
* [Common Lisp](https://github.com/ak-coram/cl-duckdb) ⭐ 55 | 🐛 4 | 🌐 Common Lisp | 📅 2026-07-29
* [Haskell](https://github.com/Tritlo/duckdb-haskell) ⭐ 22 | 🐛 6 | 🌐 Haskell | 📅 2026-04-24
* [PHP (PDO)](https://github.com/thomas-0816/pdo-duckdb-php) ⭐ 7 | 🐛 0 | 🌐 PHP | 📅 2026-08-11
* [C](https://duckdb.org/docs/clients/c/overview)
* [C++](https://duckdb.org/docs/clients/cpp)
* [CLI](https://duckdb.org/docs/clients/cli/overview)
* [Julia](https://duckdb.org/docs/clients/julia)
* [Node.js](https://duckdb.org/docs/stable/clients/node_neo/overview)
* [Python](https://duckdb.org/docs/clients/python/overview)
* [R](https://duckdb.org/docs/clients/r)
* [Swift](https://duckdb.org/docs/clients/swift)
* [WebAssembly (Wasm)](https://duckdb.org/docs/clients/wasm/overview)
* [ADBC](https://duckdb.org/docs/clients/adbc)
* [ODBC](https://duckdb.org/docs/clients/odbc/overview)

## Tools Powered by DuckDB

* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,529 | 🐛 10 | 🌐 Python | 📅 2026-08-14 - Python transpiler that translates between 24 different SQL dialects including DuckDB.
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,243 | 🐛 267 | 🌐 Python | 📅 2026-08-12 - A next-generation data transformation and modeling framework with support for DuckDB connections for state, transformations & running unit tests locally.
* [Spice.ai](https://github.com/spiceai/spiceai) ⭐ 3,065 | 🐛 626 | 🌐 Rust | 📅 2026-08-14 - A unified SQL query interface and portable runtime to locally materialize (using an embedded DuckDB), accelerate, and query datasets from any database, data warehouse, or data lake.
* [Rill Data](https://github.com/rilldata/rill) ⭐ 2,809 | 🐛 199 | 🌐 Go | 📅 2026-08-14 - Tool for effortlessly transforming data sets into powerful, opinionated dashboards using SQL.
* [Amphi ETL](https://github.com/amphi-ai/amphi-etl) ⭐ 1,391 | 🐛 128 | 🌐 TypeScript | 📅 2026-07-23 - Low-code data pipelines for structured and unstructured data. SQL transformations are powered by DuckDB.
* [Shaper](https://github.com/taleshape-com/shaper) ⭐ 1,167 | 🐛 22 | 🌐 Go | 📅 2026-08-04 - Open-source SQL-driven data dashboards, powering Taleshape, built on DuckDB.
* [Duckle](https://github.com/SouravRoy-ETL/duckle) ⭐ 1,019 | 🐛 57 | 🌐 Rust | 📅 2026-08-14 - Local-first visual ETL/ELT studio. Drag sources, transforms and sinks onto a canvas; it compiles to plain DuckDB SQL and runs entirely on DuckDB. Open source desktop app, with a built-in MCP server for generating and running pipelines from natural language.
* [Arc](https://github.com/Basekick-Labs/arc) ⭐ 639 | 🐛 39 | 🌐 Go | 📅 2026-08-14 - Time-series data warehouse built on DuckDB.
* [Huey](https://github.com/rpbouman/huey) ⭐ 607 | 🐛 111 | 🌐 JavaScript | 📅 2026-08-14 - Blazing-fast & intuitive pivot tables on Parquet, CSV, JSON files and DuckDB tables in the browser based on DuckDB-Wasm. open-source (MIT). Zero install!
* [Tailpipe](https://github.com/turbot/tailpipe) ⭐ 577 | 🐛 39 | 🌐 Go | 📅 2026-08-09 - An open-source SIEM for instant log insights.
* [Sloggo](https://github.com/phare/sloggo) ⭐ 464 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-13 - Minimal RFC 5424 syslog collector and viewer based on DuckDB. Runs as a single, resource-friendly process.
* [Phoenix Analytics](https://github.com/lalabuy948/PhoenixAnalytics) ⭐ 453 | 🐛 10 | 🌐 JavaScript | 📅 2026-03-14 - Plug and play analytics for Phoenix applications, powered by DuckDB.
* [Quackpipe](https://github.com/metrico/quackpipe) ⭐ 388 | 🐛 17 | 🌐 Go | 📅 2025-10-20 - Serverless OLAP API/UI built on top of DuckDB with basic ClickHouse API compatibility and MotherDuck support.
* [yato](https://github.com/Bl3f/yato) ⭐ 350 | 🐛 3 | 🌐 Python | 📅 2025-11-22 - The smallest DuckDB SQL orchestrator on Earth.
* [UniverSQL](https://github.com/buremba/universql) ⭐ 206 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2025-10-20 - An implementation of Snowflake API, enables running queries on Snowflake tables locally with DuckDB without a running warehouse.
* [duckdb.yazi](https://github.com/wylie102/duckdb.yazi) ⭐ 186 | 🐛 16 | 🌐 Lua | 📅 2025-05-29 - Preview csv/tsv, json, and Parquet files in the yazi file manager using duckdb. View the raw data, or a "summarized" view with data-types, min, max, avg etc. for all columns.
* [DatalakeStudio](https://github.com/javitorres/datalakeStudio) ⭐ 106 | 🐛 0 | 🌐 Vue | 📅 2026-07-30 - Load, explore, transform your datasets and expose them via API. Integration with external APIs, S3, PostgreSQL and ChatGPT.
* [HitKeep](https://github.com/PascaleBeier/hitkeep) ⭐ 81 | 🐛 9 | 🌐 Go | 📅 2026-08-11 - Open-source, privacy-first web analytics for traffic, funnels, ecommerce, Search Console, and AI visibility. Runs as a single Go binary with embedded DuckDB.
* [Whereabouts](https://github.com/ajl2718/whereabouts) ⭐ 78 | 🐛 15 | 🌐 Python | 📅 2026-08-10 - Fast, accurate, open-source geocoding in Python, using DuckDB.
* [ReportBurster](https://github.com/flowkraft/reportburster) ⭐ 76 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-11 - Business Intelligence Done Right - ReportBurster uses DuckDB as its in-process analytics database engine, and for larger workloads, supports ClickHouse too.
* [ETLX](https://github.com/realdatadriven/etlx) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2026-08-14 - DuckDB-powered ETL tool written in Go, inspired by evidence.dev's syntax. It uses a structured Markdown config where heading levels define nested blocks, yaml code blocks specify metadata, and sql code blocks handle data interactions. Enables clean, code-light orchestration with minimal setup.
* [ADPivot](https://github.com/danilo-css/analytics-data-pivot) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-08 - No code tool built on top of DuckDB-Wasm and Pyodide that helps build pivot tables from databases of any size with a few clicks.
* [DuckDB OPFS Todo List App](https://github.com/markwylde/duckdb-opfs-todo-list) ⭐ 23 | 🐛 5 | 🌐 TypeScript | 📅 2026-05-17 - A fully-functional todo list application that demonstrates DuckDB WASM OPFS (Origin Private File System) persistence using a pure functional programming approach.
* [connections.duckdb](https://github.com/tomjakubowski/connections.duckdb) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-03-06 - Play the New York Times Connections Puzzle with DuckDB.
* [geol](https://github.com/opt-nc/geol) ⭐ 12 | 🐛 22 | 🌐 HTML | 📅 2026-08-14 - A command line tool to efficiently show end-of-life dates for a number of products in your terminal using the [`endoflife.date`](https://endoflife.date) API, makes it possible to export the whole `endoflife.date` database as a fully featured DuckDB file.
* [DataCharter](https://github.com/datacharter/datacharter) ⭐ 10 | 🐛 9 | 🌐 Python | 📅 2026-08-13 - Local, contract-governed data explorer. Federates files and databases (Postgres, Snowflake, BigQuery, Excel, and more) through DuckDB — SQL editor, charts, profiling — then hands AI agents a PII-masked, read-only query surface over MCP. Apache-2.0.
* [DataSpoc Lens](https://github.com/dataspoclab/dataspoc-lens) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-28 - Virtual warehouse over cloud Parquet. SQL shell, Jupyter/Marimo notebooks, AI natural language queries, and local cache — all powered by DuckDB.
* [AnkaFlow](https://github.com/targetta/ankaflow) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - YAML-based data pipeline framework that runs both locally and fully in-browser designed for data engineers, ML teams, and SaaS developers who need flexible, SQL-powered pipelines.
* [Pondview](https://github.com/paulmupeters/pondview-bi) ⭐ 0 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-30 - Open-source, DuckDB-powered BI workspace for AI-assisted analysis, SQL, charts, and dashboards.
* [Boiling Data](https://boilingdata.com/) - Serverless data analytics overlay on top of S3 Data Lakes.
* [Hex Dataframe SQL](https://learn.hex.tech/docs/explore-data/cells/sql-cells/sql-cells-introduction) - Hex's Dataframe SQL cells are powered by DuckDB.
* [Mode](https://mode.com/blog/how-we-switched-in-memory-data-engine-to-duck-db-to-boost-visual-data-exploration-speed/) - Mode uses DuckDB for their in-memory data engine.
* [VulcanSQL](https://vulcansql.com/) - DuckDB can be used as a caching layer or a data connector in VulcanSQL, a Data API framework for data folks to create REST APIs by writing SQL templates.
* [Honeycomb Maps](https://www.honeycombmaps.com/) - A browser-based geospatial analysis tool leveraging DuckDB-Wasm.
* [Bauplan](https://www.bauplanlabs.com/) - A serverless data transformation platform for data lakes.
* [Malloy](https://www.malloydata.dev/) - Malloy is an experimental language for describing data relationships and transformations. Malloy connects to BigQuery, Snowflake, Trino, and Postgres, and natively supports DuckDB.
* [Evidence](https://evidence.dev) - Generate reports using SQL and markdown. The DuckDB connector allows querying across DuckDB, CSV, Parquet and JSON.
* [Latitude](https://latitude.so) - Latitude uses DuckDB to power data snapshots. Drop a CSV file and query it with SQL at the speed of light.
* [Census](https://www.getcensus.com/) - Census's dataset diffing for incremental syncs is powered by DuckDB.
* [Parquet Explorer](https://marketplace.visualstudio.com/items?itemName=AdamViola.parquet-explorer) - Visual Studio Code extension for exploring Parquet files with SQL, powered by DuckDB.
* [DQOps](https://dqops.com) - Data quality platform for data engineers, data quality teams and data operations.
* [Definite](https://www.definite.app/) - Definite pulls all your data into a single place for analytics and dashboards. No engineering or SQL required. Get a managed data warehouse (DuckDB), ELT, data modeling / transformations and BI in a single platform.
* [Kepler.gl](https://kepler.gl/) - Kepler.gl is a powerful open-source geospatial analysis tool for large-scale data sets, now embeds duckdb wasm to create geospatial layers.
* [Greybeam](https://www.greybeam.ai/) - Routes your Snowflake queries to a DuckDB powered warehouse to reduce costs and speed up queries.
* [Datakit](https://datakit.page/) - The privacy-first data analysis toolkit.
* [Hugr](https://hugr-lab.github.io/) - An data mesh platform and high-performance GraphQL backend powered by DuckDB.
* [Apple Embedding Atlas](https://apple.github.io/embedding-atlas/) - A tool that provides interactive visualizations for large embeddings. Uses DuckDB.
* [Boilstream](https://boilstream.com/) - Manage with SQL, like for creating topics (tables) and derived topics (materialised views) - all landing on object storage in DuckLake as optimised Parquet files.
* [Cosmograph](https://cosmograph.app/) - Beautiful visualization and analytics right in the browser.
* [Cloudspecs](https://cloudspecs.fyi/) - Live visualization tool that enables cloud system architects to answer specific instance selection questions, powered by DuckDB-Wasm.
* [Kavla](https://kavla.dev/) - A collaborative data analysis tool.
* [Enso Analytics](https://www.ensoanalytics.com/) - Dual visual/textual programming language and analytics platform, allowing DuckDB to be used as a data engine for its visual analytics and low-code workflows.
* [OpenSheet](https://opensheet.app) - Spreadsheet-style data tool with visual canvas, inline editing, and AI commands for SQL transformations.
* [Excellent Bi](https://trobee.one/ebi/) - Duck Powered simple analysis and business intelligence dashboard.  Load excel, csv, parquet files, instantly query your data in the query analyzer tool, make multiple simple dashboards.  Data stays local in OPFS local browser storage which is native to Edge and Chrome.
* [Bonnard](https://bonnard.dev) - Governed, multi-tenant MCP access to customer data. Connects DuckDB (and Snowflake, BigQuery, Postgres) to AI agents as a secure, per-customer MCP server.
* [stratif.io](https://stratif.io) - Open-source, self-hosted, warehouse-native product analytics. Runs funnels, retention, and paths on DuckDB (and Postgres, Snowflake, ClickHouse, Databricks).
* [DBConvert Streams](https://streams.dbconvert.com/) - Database IDE and migration tool with DuckDB-powered federated SQL.
* [KoliLang](https://editor.kolistat.com) - A SAS language engine (DATA step, macros, PROCs) that translates programs to DuckDB SQL — runs natively or fully in the browser on DuckDB-Wasm.

## Backends

* [DuckDB API](https://github.com/tobilg/duckdb-api) ⭐ 98 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-06 - a TypeScript-based Docker image containing DuckDB, and a Hono framework REST API with JSON or streaming Arrow responses.
* [Mosaic DuckDB Server](https://pypi.org/project/duckdb-server/) - A Python-based server that runs a local DuckDB instance and supports queries over Web Sockets or HTTP, returning data in either Apache Arrow or JSON format.
* [duckdb-server](https://lib.rs/crates/duckdb-server) - A Rust-based server that runs a local DuckDB instance and supports queries over Web Sockets or HTTP/HTTPS, returning data in either Apache Arrow or JSON format.

## Libraries Powered by DuckDB

* [smallpond](https://github.com/deepseek-ai/smallpond) ⭐ 4,983 | 🐛 34 | 🌐 Python | 📅 2025-03-05 - A distributed data processing framework by DeepSeek built on DuckDB and 3FS.
* [Splink](http://github.com/moj-analytical-services/splink) ⭐ 2,338 | 🐛 223 | 🌐 Python | 📅 2026-08-13 - A free Python library for fast, accurate data deduplication and record linkage.
* [Fugue](https://github.com/fugue-project/fugue/) ⭐ 2,170 | 🐛 53 | 🌐 Python | 📅 2026-05-19 - A unified interface for distributed computing. Fugue executes SQL, Python, Pandas, and Polars code on Spark, Dask and Ray without any rewrites.
* [Narwhals](https://github.com/narwhals-dev/narwhals) ⭐ 1,697 | 🐛 255 | 🌐 Python | 📅 2026-08-13 - Lightweight and extensible compatibility layer between dataframe libraries, supports DuckDB.
* [BemiDB](https://github.com/BemiHQ/BemiDB) ⭐ 1,530 | 🐛 11 | 🌐 Go | 📅 2026-01-07 - PostgreSQL read replica optimized for analytics, using DuckDB.
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 528 | 🐛 21 | 🌐 Python | 📅 2026-08-14 - Implements the PySpark DataFrame API in order to enable running transformation pipelines directly on database engines such as DuckDB.
* [duckdb\_fdw](https://github.com/alitrack/duckdb_fdw) ⭐ 409 | 🐛 23 | 🌐 C | 📅 2026-05-29 - DuckDB Foreign Data Wrapper for PostgreSQL.
* [QuackOSM](https://github.com/kraina-ai/quackosm) ⭐ 376 | 🐛 23 | 🌐 Python | 📅 2026-08-03 - A Python library for downloading and transforming raw OpenStreetMap data into GeoParquet files.
* [Simple-data-analysis](https://github.com/nshiab/simple-data-analysis) ⭐ 356 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-13 - Easy-to-use and high-performance JavaScript library for data analysis.
* [flapi](https://github.com/DataZooDE/flapi) ⭐ 73 | 🐛 1 | 🌐 C++ | 📅 2026-08-07 - An API Framework that heavily relies on the power of DuckDB and DuckDB extensions. Ready to build performant and cost-efficient APIs on top of BigQuery or Snowflake for AI Agents and Data Apps.
* [jsqltranspiler](https://github.com/starlake-ai/jsqltranspiler) ⭐ 73 | 🐛 15 | 🌐 Java | 📅 2026-06-14 - Rewrite BigQuery, Redshift, Snowflake and Databricks queries into DuckDB-compatible SQL.
* [Snowflake Emulator](https://github.com/nnnkkk7/snowflake-emulator) ⭐ 44 | 🐛 11 | 🌐 Go | 📅 2026-08-01 - A lightweight Snowflake emulator built with Go and DuckDB for local development and testing.
* [@jetblack/duckdb-react](https://github.com/rob-blackbourn/jetblack-duckdb-react) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-09 - A context manager for React and DuckDB-Wasm.
* [DuckDB.EFCoreProvider](https://github.com/skuirrels/DuckDB.EFCoreProvider) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2026-08-13 - Entity Framework Core provider for DuckDB and DuckLake, with LINQ, writes, migrations, bulk ingestion, and Parquet-backed tiered storage for .NET.
* [Unleasharp.DB.DuckDB](https://github.com/TraberSoftware/Unleasharp.DB.DuckDB) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-11-20 - Lightweight DuckDB query-building client for C#.
* [Omilayers](https://github.com/dkioroglou/omilayers) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-05-05 - A Python library for efficient data management that wraps the APIs of SQLite and DuckDB and offers a high-level interface analytical tasks that involve fast storage, processing and retrieval of data.
* [Ibis Project](https://ibis-project.org/) - A DataFrame API for interacting with DuckDB (and other compute engines).
* [Mosaic](https://idl.uw.edu/mosaic/) - An extensible framework for linking databases and interactive views.
* [PyGWalker](https://kanaries.net/pygwalker) - A Python library that turns your dataframe into an interactive UI for data visualization.
* [SQLRooms](https://sqlrooms.org/) - An open-source react framework for single-node data analytics powered by DuckDB.

## DuckDB Clients and UIs

### Web Clients (WebAssembly)

* [Preswald](https://github.com/StructuredLabs/preswald) ⭐ 4,280 | 🐛 330 | 🌐 Python | 📅 2026-06-11 - WASM packager for Python-based interactive data apps.
* [Medama](https://github.com/medama-io/medama) ⭐ 637 | 🐛 34 | 🌐 Go | 📅 2026-08-07 - Self-hostable, privacy-focused website analytics.
* [DuckQuery](https://github.com/Chenkeliang/duckdb-query) ⭐ 40 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Open-source visual SQL workbench to query local files (CSV/Excel/Parquet/JSON) and remote databases (MySQL/PostgreSQL) in one cross-source JOIN, plus AI text-to-SQL. Browser demo runs on DuckDB-Wasm; the full version self-hosts via Docker.
* [Joinery](https://github.com/joinery-labs/joinery) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-04 - Privacy-first local data analytics with a modern SQL editor, multi-format support (CSV, Excel, JSON, Parquet), and parameterized saved queries. Available as browser app and Tauri desktop client.
* [Online DuckDB Shell](https://shell.duckdb.org/) - Online DuckDB shell powered by DuckDB-Wasm.
* [SQL Workbench](https://sql-workbench.com) - DuckDB-Wasm based SQL Workbench for running queries on local or remote data, being able to show data as tables or visually as graphs, and sharing queries via URLs.
* [DuckDB Terminal](https://terminal.sql-workbench.com/) - Online DuckDB shell powered by DuckDB WASM and Ghostty.
* [SQL Workbench Embedded](https://embedded.sql-workbench.com) - A lightweight JavaScript library that turns SQL code blocks into interactive, browser-based database environments. Powered by DuckDB WASM.
* [Sekuel Playground](https://sekuel.com/playground/) - Query your local Parquet, CSV, JSON. Your data will not be sent out of the device you are using.
* [Codapi](https://codapi.org/duckdb/) - Embed executable code snippets directly into your product documentation, online course or blog post.
* [QuackDB](https://quackdb.com/) - Open-source online DuckDB SQL playground and editor.
* [Sidequery](https://sidequery.ai) - Sidequery is a privacy-preserving DuckDB-powered query editor & data exploration tool for local & remote data.
* [Duck-UI](https://demo.duckui.com/) - Duck-UI is a web-based interface for interacting with DuckDB with a SQL editor, data import/export, data explorer, query history, theme toggle and keyboard shortcuts.
* [SQLRooms](https://sqlrooms.org/) – React app framework for small to mid-sized data analytics powered by DuckDB-WASM.
* [PondPilot](https://pondpilot.io) - Open-source, 100% client-side data exploration tool that enables users to analyze local and remote data using SQL. Zero-copy direct access to local datasets sets PondPilot apart from similar tools. It runs entirely in the browser—no servers, no cloud uploads, and no setup required.
* [TabulaStudio](https://tabulastudio.com) - Browser-only enterprise data analytics platform with Jupyter-style notebooks, AI-powered visualizations, and enterprise performance (10M+ rows/second). Direct access to files and live databases like (Neon and Supabase ) without servers, cloud uploads, or setup—your data never leaves your browser.
* [dbxlite](https://dbxlite.com/) - DuckDB workbench for native & browser.
* [csvtodashboard](https://csvtodashboard.com/csv-sql-query) - Free SQL-on-CSV in the browser via DuckDB-Wasm — no signup, no upload, files stay on-device.
* [ParquetKit](https://parquetkit.com) - Browser-based Parquet viewer, SQL workbench and converter powered by DuckDB-Wasm. Fully client-side — files never leave your device.
* [Bedevere](https://bedeverewise.app) - Tabular data visualizer and DuckDB SQL editor on DuckDB-Wasm: open CSV/Parquet/JSON/Arrow locally, chart results with a grammar-of-graphics `VISUALIZE` syntax, and embed it anywhere via npm component or a one-line iframe.

## SQL Clients and IDE that Support DuckDB

* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,274 | 🐛 17 | 🌐 Rust | 📅 2026-08-08 - A database TUI with experimental support for DuckDB.
* [Duckling](https://github.com/l1xnan/duckling) ⭐ 576 | 🐛 60 | 🌐 TypeScript | 📅 2026-08-13 - A fast viewer for CSV/Parquet files and DuckDB/SQLite, based on Tauri.
* [rsql](https://github.com/theseus-rs/rsql) ⭐ 449 | 🐛 11 | 🌐 Rust | 📅 2026-07-26 - CLI for DuckDB, LibSQL, MariaDB, MySQL, PostgreSQL, SQLite3 and SQL Server.
* [DuckDB SQL Tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools) - Free DuckDB SQL Tools for VS Code IDE. [Premium version available](https://github.com/RandomFractals/pro-data-tools/blob/main/duckdb-tools.md#duckdb-pro-tools) ⭐ 42 | 🐛 2 | 📅 2024-07-14 with advanced features.
* [tuitab](https://github.com/denisotree/tuitab) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-08-13 - A Rust TUI for fast, in-depth analytics on large datasets (CSV, JSON, Parquet, Excel, SQLite) powered by DuckDB.
* [AmoxSQL](https://github.com/DSandovalFlavio/AmoxSQL) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-11 - The Modern Codex for Local Data Analysis. A high-performance, local-first IDE built specifically for DuckDB.
* [Harlequin](https://harlequin.sh) - The DuckDB IDE (TUI) for your terminal.
* [qStudio](https://www.timestored.com/qstudio/) - A free SQL tool specialized for data analysts. It runs on every operating system and allows easy browsing of tables and charting of results.
* [VSCode SQLTools](https://marketplace.visualstudio.com/items?itemName=Evidence.sqltools-duckdb-driver) - Free open-source VSCode extension to query and explore your DuckDB databases with latest DuckDB support.
* [DBeaver](https://dbeaver.com) - DBeaver is a universal database access and development tool that can be used to connect almost any type of database.
* [DataGrip](https://www.jetbrains.com/datagrip/) - Paid SQL IDE by JetBrains that supports many different database technologies, including DuckDB.
* [SQL DATA LENS](https://sqldatalens.com/build-in-support-for-duckdb/) - A lightweight, commercial SQL IDE that supports different DBMS, including DuckDB. The focus is on performance and special DBMS features.
* [Dataflare](https://dataflare.app) - Simple easy-to-use database manager, supports DuckDB, PostgreSQL, MySQL, SQL Server, SQLite etc.
* [marimo](https://marimo.io) - Unified data & AI platform that lets you work with SQL and Python with native support for DuckDB.
* [jupysql](https://pypi.org/project/jupysql/) - Run SQL in Jupyter/IPython via a %sql and %%sql magics, with support for DuckDB.
* [magic\_duckdb](https://pypi.org/project/magic-duckdb/) - DuckDB native %dql and %%dql magics for Jupyter/IPython.
* [Tad](https://www.tadviewer.com) - A fast, free, cross-platform tabular data viewer application powered by DuckDB.

## Projects Powered by DuckDB

* [msgvault](https://github.com/wesm/msgvault) ⭐ 2,007 | 🐛 86 | 🌐 Go | 📅 2026-08-14 - Archive a lifetime of email and chat. Offline search, analytics, and AI query over your full message history. Powered by DuckDB.
* [NBA Monte Carlo](https://github.com/matsonj/nba-monte-carlo) ⭐ 607 | 🐛 1 | 🌐 Python | 📅 2026-07-27 - Monte Carlo simulation of the NBA season, leveraging Meltano, dbt, DuckDB and Evidence.
* [`transfermarkt-datasets`](https://github.com/dcaribou/transfermarkt-datasets) ⭐ 471 | 🐛 51 | 🌐 Python | 📅 2026-08-05 - Curated football datasets from [Transfermarkt](https://www.transfermarkt.co.uk/).
* [Datadex](https://github.com/davidgasquez/datadex/) ⭐ 315 | 🐛 0 | 🌐 HTML | 📅 2026-06-06 - Open-source and local-friendly data platform to collaborate on Open Data using DuckDB, Dagster, dbt, and Quarto.
* [Ducklings](https://github.com/tobilg/ducklings) ⭐ 246 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-10 - A minimal DuckDB WASM build for browsers and serverless environments like Cloudflare Workers.
* [duckdb-embedding-search](https://github.com/patricktrainer/duckdb-embedding-search) ⭐ 150 | 🐛 4 | 🌐 Python | 📅 2024-10-30 - A search engine for DuckDB that uses embedding vectors to find similar documents.
* [duckdb-claude-slack](https://github.com/sidequery/duckdb-claude-slack) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-12-10 - A Slack data analysis agent powered by DuckDB and Claude Code.
* [PyStack't](https://github.com/LienBosmans/pystackt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-01-12 - Python package that supports data preparation for object-centric process mining.
* [datagenerator2](https://github.com/uwegeercken/datagenerator2) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2026-05-01 - Generates random data, allowing to define dependencies between individual fields and varying/definable distribution of field values.
* [Overture Places UA](https://github.com/xtrustinfo/overture-places-ua) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-08-05 - Extract all Ukrainian POIs from Overture Maps releases into CSV or Parquet with a single DuckDB query.
* [`endoflife.date` database](https://www.kaggle.com/datasets/adriensales/endoflife-date-database) - Daily dumps of endoflife.date data.
* [DuckDB PyPI stats live dashboard](https://duckdbstats.com/) - Live dashboard of PyPI downloads using DuckDB, dbt, Evidence and MotherDuck with code source to build your own.
* [Georgia State University Book Prices](https://crimede-coder.com/graphs/GSUBooksQuery) - DuckDB powered WASM app where you can search how much students spend on books at Georgia State University.

## Integrations

* [MindsDB](https://github.com/mindsdb/mindsdb) ⭐ 39,569 | 🐛 3 | 🌐 Makefile | 📅 2026-08-13 - The platform for customizing AI from enterprise data. [MindsDB integrates with DuckDB](https://docs.mindsdb.com/integrations/data-integrations/duckdb), making data from DuckDB accessible to a diverse range of AI/ML models.
* [manifold-sql (DuckDB for Java)](https://github.com/manifold-systems/manifold/blob/master/docs/articles/duckdb_info.md) ⭐ 2,759 | 🐛 110 | 🌐 Java | 📅 2026-08-14 - Use native DuckDB SQL of any complexity directly & type-safely in Java source with comprehensive IntelliJ support.
* [dbt-duckdb](https://github.com/jwills/dbt-duckdb) ⭐ 1,334 | 🐛 82 | 🌐 Python | 📅 2026-08-12 - DuckDB dbt adapter.
* [SQLFlow](https://github.com/turbolytics/sql-flow) ⭐ 783 | 🐛 33 | 🌐 Python | 📅 2025-09-04 - Enables SQL-based stream processing, powered by DuckDB.
* [metabase\_duckdb\_driver](https://github.com/MotherDuck-Open-Source/metabase_duckdb_driver) ⭐ 167 | 🐛 19 | 🌐 Clojure | 📅 2026-08-14 - Metabase DuckDB Driver shipped as 3rd party plugin.
* [kwack](https://github.com/rayokota/kwack) ⭐ 155 | 🐛 12 | 🌐 Java | 📅 2026-02-16 - In-Memory Analytics for Kafka using DuckDB.
* [xlDuckDb](https://github.com/RusselWebber/xlDuckDb) ⭐ 147 | 🐛 1 | 🌐 C# | 📅 2026-08-14 - Excel addin to run DuckDB queries in Excel.
* [Sidemantic](https://github.com/sidequery/sidemantic) ⭐ 113 | 🐛 1 | 🌐 Python | 📅 2026-08-06 - A semantic layer with DuckDB integration.
* [duckdb-power-query-connector](https://github.com/MotherDuck-Open-Source/duckdb-power-query-connector) ⭐ 89 | 🐛 7 | 🌐 Power Query | 📅 2026-07-29 - DuckDB Power Query Custom Connector.
* [OrionBelt Semantic Layer](https://github.com/ralfbecher/orionbelt-semantic-layer) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2026-08-11 - Open-source semantic sidecar that compiles YAML semantic models to optimized SQL across 8 engines including DuckDB. Ships with an `ob-duckdb` driver, REST + Arrow Flight SQL + Postgres wire surfaces, and a baked-in DuckDB quickstart on Colab.
* [PSDuckDB](https://github.com/dfinke/PSDuckDB) ⭐ 61 | 🐛 2 | 🌐 PowerShell | 📅 2024-09-10 - A PowerShell module for DuckDB integration.
* [nf-sqldb](https://github.com/nextflow-io/nf-sqldb) ⭐ 32 | 🐛 16 | 🌐 Groovy | 📅 2026-08-10 - This plugin provides support for interacting with SQL databases in Nextflow scripts.
* [sqlite2duckdb](https://github.com/dridk/sqlite2duckdb) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2024-05-23 - A CLI tool to convert SQLite database to DuckDB.
* [duckdb-tableau-connector](https://github.com/MotherDuck-Open-Source/duckdb-tableau-connector) ⭐ 23 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-12 - DuckDB Tableau connector.
* [Hasura DuckDB Connector](https://github.com/hasura/ndc-duckdb) ⭐ 19 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-12 - Allows connecting to a DuckDB database or a MotherDuck-hosted DuckDB database through a GraphQL API.
* [duckdb-teradata](https://github.com/duckdb/duckdb-teradata) ⭐ 15 | 🐛 4 | 🌐 C | 📅 2025-11-17 - Teradata connector.
* [DuckDB VBA](https://github.com/EtienneLenoir/duckdb-vba) ⭐ 9 | 🐛 0 | 🌐 VBA | 📅 2026-06-11 - Excel/VBA integration for DuckDB using the native C API through a lightweight DLL bridge. Supports Range/Array ingestion, dictionary lookups, Parquet/CSV/JSON workflows, SQLite/PostgreSQL connectivity, and Access-to-DuckDB migration.
* [data load tool - DuckDB destination](https://dlthub.com/docs/dlt-ecosystem/destinations/duckdb) - Extract and load data from APIs to DuckDB using dlt.
* [target-duckdb](https://hub.meltano.com/loaders/target-duckdb/) - Load data to DuckDB based on Singer spec.
* [Airbyte DuckDB destination](https://docs.airbyte.com/integrations/destinations/duckdb/) - Load data to DuckDB with Airbyte.
* [Kestra DuckDB plugin](https://kestra.io/plugins/plugin-jdbc-duckdb) - Run queries with DuckDB to schedule data transformations and process automations and run event-driven anomaly detection pipelines.
* [nodbi](https://docs.ropensci.org/nodbi/) - NoSQL Database Connector for R, providing a common API across Elasticsearch, CouchDB, MongoDB, SQLite, PostgreSQL, and DuckDB.
* [duckplyr](https://tidyverse.github.io/duckplyr/) - Drop-in replacement for dplyr in R that uses DuckDB for performance.
* [Ontop](https://ontop-vkg.org/guide/databases/duckdb.html) - Allows to create Virtual Knowledge Graphs directly from DuckDB.
* [jOOQ](https://www.jooq.org/) - Type safe querying of DuckDB (and many other RDBMS) from Java. A [transpiler](https://www.jooq.org/translate/) from and to DuckDB is also available.
* [The Quack is Back: SAS/ACCESS Meets DuckDB](https://communities.sas.com/t5/SAS-Communities-Library/The-Quack-is-Back-SAS-ACCESS-Meets-DuckDB/ta-p/969374) - SAS/ACCESS engine support for DuckDB.
* [Kotlin DataFrame](https://kotlin.github.io/dataframe/duckdb.html) - Supports reading from DuckDB databases using JDBC.
* [Cloudflare R2 Data Catalog connector](https://developers.cloudflare.com/r2/data-catalog/config-examples/duckdb/) - Connect to Cloudflare R2 Data Catalog with DuckDB.
* [Enrich.sh](https://enrich.sh) - Lightweight event ingestion that stores JSON events as Parquet in R2, queryable directly from DuckDB.

## Client-Server Setups

* [AliSQL](https://github.com/alibaba/AliSQL) ⭐ 5,870 | 🐛 18 | 🌐 C++ | 📅 2026-07-18 - A MySQL branch originated from Alibaba Group. Integrates DuckDB as a native storage engine.
* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,189 | 🐛 113 | 🌐 C++ | 📅 2026-07-17 - DuckDB-powered PostgreSQL for high-performance apps & analytics.
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 1,999 | 🐛 14 | 🌐 Rust | 📅 2026-03-31 - A PostgreSQL extension that adds native column store tables with DuckDB.
* [pg\_lake](https://github.com/snowflake-labs/pg_lake) ⭐ 1,612 | 🐛 104 | 🌐 Python | 📅 2026-08-14 - `pg_lake` integrates Iceberg and data lake files into Postgres. Uses DuckDB to execute queries.
* [MyDuck Server](https://github.com/apecloud/myduckserver) ⭐ 581 | 🐛 41 | 🌐 Go | 📅 2025-01-17 - A server wrapping DuckDB with MySQL and PostgreSQL wire protocol support.
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - PostgreSQL extension embedding DuckDB-in-PostgreSQL for fast on-disk and remote object storage analytics from Postgres. Built as a Foreign Data Wrapper with full query pushdown to DuckDB. Integrates easily with ParadeDB.
* [GizmoSQL - Arrow Flight SQL Server](https://github.com/gizmodata/gizmosql) ⭐ 357 | 🐛 5 | 🌐 C++ | 📅 2026-07-31 - A C++ implementation of the [Arrow Flight SQL protocol](https://arrow.apache.org/docs/format/FlightSql.html) that runs in a client-server setup with DuckDB or SQLite as backends.
* [Porter](https://github.com/TFMV/porter) ⭐ 150 | 🐛 5 | 🌐 Go | 📅 2026-07-25 - A Go-based implementation of a DuckDB Arrow Flight SQL Server.
* [Crunchy Data Warehouse](https://www.crunchydata.com/products/warehouse) - Fully managed DBaaS based in PostgreSQL integrated with DuckDB.
* [MotherDuck](https://motherduck.com/) - A serverless cloud data warehouse powered by DuckDB.
* [Termux DuckDB package](https://packages.termux.dev/apt/termux-main/pool/main/libd/libduckdb/) - DuckDB CLI client for the Termux Android terminal emulator.
* [rawquery](https://rawquery.dev) - Managed analytical platform pairing DuckDB compute with Iceberg storage on S3. Postgres wire protocol, CLI, and Python API.
* [Layerbase](https://layerbase.com) - Managed DuckDB hosting with a browser query console, REST API and CLI, alongside 17 other database engines under one account. Databases scale to zero when idle and wake on connect.

## Extensions

### [Core Extensions](https://duckdb.org/docs/stable/core_extensions/overview)

Official DuckDB extensions, which can installed via `INSTALL ⟨extension_name⟩`.

* [`ducklake`](https://github.com/duckdb/ducklake) ⭐ 2,915 | 🐛 164 | 🌐 C++ | 📅 2026-08-13 - For DuckLake support.
* [`iceberg`](https://github.com/duckdb/duckdb_iceberg) ⭐ 426 | 🐛 81 | 🌐 C++ | 📅 2026-08-14 - For reading Iceberg tables.
* [`delta`](https://github.com/duckdb/duckdb_delta) ⭐ 228 | 🐛 61 | 🌐 C++ | 📅 2026-08-14 - For Delta Lake support.
* [`azure`](https://github.com/duckdb/duckdb_azure) ⭐ 77 | 🐛 36 | 🌐 C++ | 📅 2026-08-12 - For using the Azure Blob storage.
* [`aws`](https://github.com/duckdb/duckdb_aws) ⭐ 64 | 🐛 31 | 🌐 C++ | 📅 2026-08-12 - For handling AWS credentials.
* [`arrow`](https://github.com/duckdb/arrow) ⭐ 46 | 🐛 3 | 🌐 C++ | 📅 2025-05-12 - A zero-copy data integration between Apache Arrow and DuckDB.
* [`avro`](https://github.com/duckdb/duckdb-avro) ⭐ 35 | 🐛 6 | 🌐 C++ | 📅 2026-08-07 - For reading Avro files.
* [`inet`](https://github.com/duckdb/duckdb_inet) ⭐ 14 | 🐛 13 | 🌐 C++ | 📅 2025-11-20 - For storing and handling IPv4 and IPv6 Internet addresses.
* [`fts`](https://duckdb.org/docs/extensions/full_text_search) - To support full-text search.
* [`json`](https://duckdb.org/docs/stable/data/json/overview) - For reading and writing JSON data.
* [`mysql`](https://duckdb.org/docs/extensions/mysql) - To read from and write to MySQL databases.
* [`parquet`](https://duckdb.org/docs/stable/data/parquet/overview) - For reading and writing Parquet data.
* [`postgres`](https://duckdb.org/docs/extensions/postgres) - To read from and write to PostgreSQL databases.
* [`spatial`](https://duckdb.org/docs/extensions/spatial) - Enables geospatial processing.
* [`sqlite`](https://duckdb.org/docs/extensions/sqlite) - To read from and write to SQLite databases.
* [`vss`](https://duckdb.org/docs/extensions/vss) - Add support for vector similarity search.

### [Community Extensions](https://duckdb.org/community_extensions/)

Community-contributed DuckDB extensions, which can be installed via `INSTALL ⟨extension_name⟩ FROM community`.

* [`duckpgq`](https://github.com/cwida/duckpgq-extension) ⭐ 472 | 🐛 30 | 🌐 C++ | 📅 2026-08-14 - Add supports for SQL/PGQ (Property Graph Queries) introduced in the SQL:2023 standard.
* [`gsheets`](https://github.com/evidence-dev/duckdb_gsheets) ⭐ 349 | 🐛 11 | 🌐 C++ | 📅 2026-02-21 - Read and write Google Sheets using SQL.
* [`prql`](https://github.com/ywelsch/duckdb-prql) ⭐ 328 | 🐛 4 | 🌐 C++ | 📅 2026-05-28 - Run PRQL commands directly within DuckDB.
* [`httpserver`](https://github.com/quackscience/duckdb-extension-httpserver) ⭐ 284 | 🐛 12 | 🌐 C++ | 📅 2026-07-26 - DuckDB HTTP API Server and Query Interface.
* [`h3`](https://github.com/isaacbrodsky/h3-duckdb) ⭐ 251 | 🐛 14 | 🌐 C | 📅 2026-07-22 - Adds support for the H3 discrete global grid system.
* [`bigquery`](https://github.com/hafenkran/duckdb-bigquery) ⭐ 166 | 🐛 7 | 🌐 C++ | 📅 2026-08-09 - Integrates DuckDB with Google BigQuery, allowing direct querying and management of BigQuery datasets.
* [`scrooge`](https://github.com/pdet/Scrooge-McDuck) ⭐ 162 | 🐛 1 | 🌐 C++ | 📅 2026-05-04 - A set of aggregation functions and data scanners on financial data.
* [`onager`](https://github.com/CogitatorTech/onager) ⭐ 148 | 🐛 3 | 🌐 Rust | 📅 2026-07-30 - A DuckDB extension for graph data analytics.
* [`cache_httpfs`](https://github.com/dentiny/duck-read-cache-fs) ⭐ 143 | 🐛 13 | 🌐 C++ | 📅 2026-08-06 - Adds a read caching layer to duckdb filesystem to improve query performance and reduce egress cost.
* [`infera`](https://github.com/CogitatorTech/infera) ⭐ 135 | 🐛 5 | 🌐 Rust | 📅 2026-07-22 - A DuckDB extension for in-database inference.
* [`shellfs`](https://github.com/rustyconover/duckdb-shellfs-extension) ⭐ 95 | 🐛 3 | 🌐 C++ | 📅 2026-07-25 - Allows shell commands to be used for input and output.
* [`chsql`](https://github.com/lmangani/duckdb-extension-clickhouse-sql) ⭐ 93 | 🐛 2 | 🌐 C++ | 📅 2026-02-18 - ClickHouse SQL Dialect macros for DuckDB.
* [`dash`](https://github.com/gropaul/dash) ⭐ 91 | 🐛 1 | 🌐 C++ | 📅 2026-08-13 - Fully local data canvas and dashboarding app within DuckDB.
* [`lindel`](https://github.com/rustyconover/duckdb-lindel-extension) ⭐ 66 | 🐛 0 | 🌐 C++ | 📅 2026-07-25 - Linearization/Delinearization, Z-Order, Hilbert and Morton Curves.
* [`duckherder`](https://github.com/dentiny/duckdb-distributed-execution) ⭐ 60 | 🐛 18 | 🌐 C++ | 📅 2026-03-10 - Distributed execution for DuckDB queries.
* [`yardstick`](https://github.com/sidequery/yardstick) ⭐ 58 | 🐛 0 | 🌐 Rust | 📅 2026-07-03 - Implements Measures in SQL paper as a DuckDB extension for centralized metric definitions / en embedded semantic layer.
* [`acp`](https://github.com/sidequery/duckdb-acp) ⚠️ Archived - Embeds AI agents such as Claude Code inside of DuckDB via Agent Client Protocol.
* [`stats_duck`](https://github.com/KoliStat/the-stats-duck) ⭐ 55 | 🐛 18 | 🌐 C++ | 📅 2026-08-14 - Statistics for tabular and clinical data: descriptive tables (`table_one`), linear models with robust/clustered standard errors, meta-analysis, bootstrap, and a grammar-of-graphics `VISUALIZE` clause that turns queries into Vega-Lite charts.
* [`netquack`](https://github.com/hatamiarash7/duckdb-netquack) ⭐ 42 | 🐛 2 | 🌐 C++ | 📅 2026-07-25 - Parsing, extracting, and analyzing domains, URIs, and paths with ease.
* [`3fs`](https://github.com/open3fs/duckdb-3fs) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2025-05-16 - Integrates DuckDB with DeepSeek 3FS distributed file system.
* [`hostfs`](https://github.com/gropaul/hostfs) ⭐ 31 | 🐛 1 | 🌐 C++ | 📅 2025-10-01 - Navigate and explore the local filesystem using SQL.
* [`crypto`](https://github.com/rustyconover/duckdb-crypto-extension) ⭐ 30 | 🐛 1 | 🌐 C++ | 📅 2026-07-25 - Cryptographic hash functions and HMAC.
* [`fuzzycomplete`](https://github.com/rustyconover/duckdb-fuzzycomplete-extension) ⭐ 29 | 🐛 0 | 🌐 C++ | 📅 2026-07-25 - Performs fuzzy string matching for autocompletion.
* [`evalexpr_rhai`](https://github.com/rustyconover/duckdb-evalexpr-rhai-extension) ⭐ 26 | 🐛 2 | 🌐 C++ | 📅 2026-07-25 - Evaluates the [Rhai](https://rhai.rs) scripting language as part of SQL.
* [`ulid`](https://github.com/Maxxen/duckdb_ulid) ⭐ 25 | 🐛 2 | 🌐 C++ | 📅 2024-07-09 - ULID data type for DuckDB. A ULID is similar to a UUID except that it also contains a timestamp component.
* [`elasticsearch`](https://github.com/tlinhart/duckdb-elasticsearch) ⭐ 21 | 🐛 5 | 🌐 C++ | 📅 2026-04-29 - Query Elasticsearch indices directly using SQL.
* [`gaggle`](https://github.com/CogitatorTech/gaggle) ⭐ 17 | 🐛 2 | 🌐 Rust | 📅 2026-07-22 - A DuckDB extension for working with Kaggle datasets.
* [`observefs`](https://github.com/dentiny/duckdb-filesystem-observability) ⭐ 16 | 🐛 2 | 🌐 C++ | 📅 2026-07-25 - I/O observability for DuckDB filesystems with latency statistics and external file cache access insights.
* [`curl_httpfs`](https://github.com/dentiny/duckdb-curl-filesystem) ⭐ 12 | 🐛 3 | 🌐 C++ | 📅 2026-07-25 - Enhanced HTTP file system with connection pooling, HTTP/2 support, and asynchronous I/O operations.
* [`pst`](https://github.com/intellekthq/duckdb-pst) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-08-03 - Read Microsoft PST files in-place with rich schemas for emails, contacts, appointments, tasks, and more.
* [`cache_prewarm`](https://github.com/dentiny/duckdb-cache-prewarm) ⭐ 9 | 🐛 12 | 🌐 C++ | 📅 2026-07-28 - A Preloads table data blocks into the buffer pool or OS page cache, inspired by PostgreSQL's pg\_prewarm extension.
* [`pfc`](https://github.com/ImpossibleForge/pfc-duckdb) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-05-19 - Read block-indexed PFC-compressed JSONL logs with timestamp filtering — 25% smaller than gzip with minimal S3 egress.

### Other Extensions

* [Kùzu](https://github.com/kuzudb/kuzu/tree/master/extension/duckdb) ⚠️ Archived - Scan DuckDB tables in Kùzu, an embeddable property graph database management system.
* [duckdb\_engine](https://github.com/Mause/duckdb_engine) ⭐ 495 | 🐛 97 | 🌐 Python | 📅 2026-08-14 - SQLAlchemy driver for DuckDB.
* [FlockMTL](https://github.com/dsg-polymtl/flockmtl) ⭐ 353 | 🐛 26 | 🌐 C++ | 📅 2026-07-26 - Integrate language model (LLM) capabilities directly into your queries and workflows.
* [UC Catalog Extension](https://github.com/duckdb/uc_catalog) ⭐ 108 | 🐛 32 | 🌐 C++ | 📅 2026-08-14 - Proof-of-concept extension combining the `delta` extension with Unity Catalog.
* [duckdb-pytables](https://github.com/MarkRoddy/duckdb-pytables) ⭐ 92 | 🐛 7 | 🌐 C++ | 📅 2024-05-03 - DuckDB extension to allow running SQL on arbitrary data sources.
* [ODBC Scanner DuckDB Extension](https://github.com/rupurt/odbc-scanner-duckdb-extension) ⭐ 89 | 🐛 23 | 🌐 C++ | 📅 2023-09-04 - DuckDB extension to read data directly from databases supporting the ODBC interface.
* [go-duckfs](https://github.com/firetiger-oss/go-duckfs) ⭐ 63 | 🐛 1 | 🌐 Go | 📅 2026-07-09 - A Go library that mounts `io/fs` file systems as DuckDB virtual file systems, sandboxing all I/O through the Go runtime.
* [DuckDB.ExtensionKit](https://github.com/Giorgi/DuckDB.ExtensionKit) ⭐ 53 | 🐛 1 | 🌐 C# | 📅 2026-03-09 - Build native DuckDB extensions in C#.
* [duckdb-extension-template-zig](https://github.com/rupurt/duckdb-extension-template-zig) ⭐ 36 | 🐛 1 | 🌐 Nix | 📅 2024-03-16 - A Zig & Nix toolkit template for building extensions against multiple versions of DuckDB using Zig, C or C++.
* [duckdb\_protobuf](https://github.com/0xcaff/duckdb_protobuf) ⭐ 30 | 🐛 6 | 🌐 Rust | 📅 2025-07-21 - Plugin for querying encoded protobuf messages (both sequences and individual messages per file).
* [ERPL Web](https://github.com/DataZooDE/erpl-web) ⭐ 29 | 🐛 2 | 🌐 C++ | 📅 2026-08-10 - ERPL Web is a DuckDB extension that connects API-based ecosystems via standard interfaces like OData, GraphQL, and REST.
* [quack-zig](https://github.com/mlafeldt/quack-zig) ⭐ 23 | 🐛 0 | 🌐 Zig | 📅 2025-10-07 - The infamous DuckDB quack extension rewritten in C and built with Zig. Proof that you can develop DuckDB extensions without drowning in boilerplate.
* [duckdb-jfr-extension](https://github.com/ocadaruma/duckdb-jfr-extension) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2024-10-15 - DuckDB extension to read JFR (Java Flight Recorder) files directly.
* [template-duckdb-extension-zig](https://github.com/habedi/template-duckdb-extension-zig) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2026-07-29: A template for developing DuckDB extensions in Zig using DuckDB's C API.
* [ERPL](https://erpl.io) - DuckDB SAP connector using RFC, ODP, or BICS.
* [Lance](https://docs.lancedb.com/integrations/data/duckdb) - Integrate Lance (modern columnar data format for ML implemented in Rust) with DuckDB.
* [QDuckDB](https://gitlab.com/Oslandia/qgis/qduckdb) - Plugin for reading DuckDB spatial tables in QGIS software.

### Extension Statistics

* [DuckDB Extension Radar](https://github.com/mehd-io/duckdb-extension-radar) ⭐ 115 | 🐛 1 | 🌐 Python | 📅 2026-08-14 - Repository that contains DuckDB extensions on GitHub. Refreshed daily.
* [DuckDB extension weekly downloads](https://duckdb-ce-analysis.evidence.app/) - Statistics of weekly downloads for core extensions and community extensions. Refreshed daily.

## Tutorials

* [DBQuacks](https://dbquacks.com/tutorial/1) - An interactive SQL tutorial powered by DuckDB.
* [GeoSQL](https://geosql.dev) - Interactive spatial SQL problems powered by DuckDB-WASM, running entirely in the browser.

## Media

### Talks

* [DuckLake - The SQL-Powered Lakehouse Format for the Rest of Us](https://www.youtube.com/watch?v=YQEUkFWa69o) - Hannes Mühleisen.
* [Introducing DuckLake](https://www.youtube.com/watch?v=zeonmOO9jm4) - Hannes Mühleisen and Mark Raasveldt.
* [DuckCon #6 playlist](https://www.youtube.com/playlist?list=PLzIMXBizEZjggaDzjPP542En2R5SV0WiZ)
* [DuckDB: Crunching data anywhere from laptops to servers @ GOTO Amsterdam 2024](https://www.youtube.com/watch?v=9Rdwh0rNaf0) - Gábor Szárnyas.
* [DuckDB – Overview and latest developments @ DuckCon #5](https://www.youtube.com/watch?v=xX6qnP2H5wk) - Hannes Mühleisen and Mark Raasveldt.
* [DuckCon #5 playlist](https://www.youtube.com/playlist?list=PLzIMXBizEZjhbacz4PWGuCUSxizmLei8Y)
* [DuckCon #4 playlist](https://www.youtube.com/playlist?list=PLzIMXBizEZjhZcTiEFZIAxPpB6RE9TmgC)
* [DuckCon #3 playlist](https://www.youtube.com/playlist?list=PLzIMXBizEZjhy6QG4Eqoe9k9NgBa-w67Y)
* [In-Process Analytical Data Management with DuckDB @ PyData Amsterdam](https://www.youtube.com/watch?v=5ddoZR6PYNU) - Hannes Mühleisen.
* [DuckDB: The Power of a Data Warehouse in your Python Process @ PyData Yerevan](https://www.youtube.com/watch?v=q_SKaOeRiOI) - Gábor Szárnyas.
* [DuckDB: Bringing analytical SQL directly to your Python shell @ EuroPython](https://www.youtube.com/watch?v=egN4TwVyJss) - Pedro Holanda.
* [DuckDB keynote @ Data + AI Summit 2023](https://www.youtube.com/watch?v=GaHWuQ_cBhA) - Hannes Mühleisen.
* [DuckDB: Bringing Analytical SQL Directly To Your Python Shell @ FOSDEM](https://www.youtube.com/watch?v=-rCZQHXSunc) - Pedro Holanda.
* [State of the Duck @ DuckCon #2](https://www.youtube.com/watch?v=rdnPkLSkoyU) - Hannes Mühleisen & Mark Raasveldt.
* [DuckDB Extensions @ DuckCon](https://www.youtube.com/watch?v=UKo_LQyLTko) - Pedro Holanda & Sam Ansmink.
* [Developing Systems in Academia: The Good, the Bad, and the not-so-Ugly Duckling @ CIDR](https://www.youtube.com/watch?v=dv4A2LIFG80) - Hannes Mühleisen.
* [DuckDB An Embeddable Analytical Database @ FOSDEM](https://www.youtube.com/watch?v=nPDomZQ8jI4) - Hannes Mühleisen.
* [DuckDB tutorials playlist by Learn Data with Mark](https://www.youtube.com/watch?v=fZj6kTwXN1U\&list=PLw2SS5iImhEThtiGNPiNenOr2tVvLj6H7) - Mark Needham.
* [DuckDB tutorials playlist by MotherDuck](https://www.youtube.com/playlist?list=PLIYcNkSjh-0wlrFUE2VvQilLU2aBPns0K) - Mehdi Ouazza.
* [Nextflow and database uses: powering data engineering, exploring DuckDB, and beyond](https://youtu.be/GknH1u3NtGI?si=PKnF__cQJ_citMUi) - Edmund Miller.
* [Why should you care about DuckDB? @ Dublin DuckDB meetup](https://www.youtube.com/watch?v=q55UMyQapKA) - Mihai Bojin.
* [Exploring Monte Carlo Simulations With DuckDB @ Dublin DuckDB meetup](https://www.youtube.com/watch?v=oh0Y3MN2Tas) - James McNeill.
* [DuckDB and recommenders: A lightning fast synergy @ Dublin DuckDB meetup](https://www.youtube.com/watch?v=Y3aJe8MRKAI) - Khalil Muhammad.

### Podcasts

* [Developer Voices: Implementing Hardware-Friendly Databases](https://www.youtube.com/watch?v=pZV9FvdKmLc) - Hannes Mühleisen.
* [The Geek Narrator: DuckDB Internals](https://www.youtube.com/watch?v=f9QlkXW4H9A) - Mark Raasveldt.
* [Software Engineering Daily: DuckDB](https://softwareengineeringdaily.com/2022/03/18/duckdb-with-hannes-muleisen/) - Hannes Mühleisen.
* [Data Engineering Podcast: Move Your Database To The Data And Speed Up Your Analytics With DuckDB](https://www.dataengineeringpodcast.com/duckdb-in-process-olap-database-episode-270/) - Hannes Mühleisen.
* [The Analytics Engineering Podcast: The Personal Data Warehouse](https://www.youtube.com/watch?v=4aRdCfrNjMk) - Jordan Tigani.
* [DuckDB in Research](https://shows.acast.com/disseminate) - Series in Disseminate, the Computer Science Research Podcast, with host Jack Waudby.

### Blog Posts

* [Duck Takes Flight: Streaming Data in DuckDB](https://www.definite.app/blog/duck-takes-flight) - Adding concurrent read/write to DuckDB with Arrow Flight.
* [Modern Data Stack in a Box](https://duckdb.org/2022/10/12/modern-data-stack-in-a-box.html) -  Fast, free, and open-source Modern Data Stack deployed on a laptop using the combination of DuckDB, Meltano, dbt, and Apache Superset.
* [How to use DuckDB, Motherduck and Kestra for ETL](https://motherduck.com/blog/motherduck-kestra-etl-pipelines/) - How DuckDB can transform data, mask sensitive PII information, detect anomalies in event-driven workflows, and streamline reporting use cases.
* [DuckDB vs. MotherDuck — how do they compare](https://kestra.io/blogs/2023-07-28-duckdb-vs-motherduck) - What are the key differences between them, and when to choose each of these options.
* [Building DuckDB Extensions with Zig and Nix](https://rupurt.github.io/posts/building-duckdb-extensions-with-zig-and-nix) - For Nix users and Zig developers familiar with DuckDB looking to extend its capabilities with custom extensions.
* [Exploring StarCraft 2 data with Airflow, DuckDB and Streamlit](https://medium.com/data-engineer-things/exploring-starcraft-2-data-with-airflow-duckdb-and-streamlit-7c0ad79f9ca6) - Example project using DuckDB to persist API data, but also explains how to use DuckDB as a versatile data manipulation tool in data wrangling scripts.
* [DuckDB: The Rising Star in the Big Data Landscape](https://mihaibojin.medium.com/duckdb-the-big-data-rising-star-71916f953f18)
* [DuckDB Doesn't Need Data To Be a Database](https://www.nikolasgoebel.com/2024/05/28/duckdb-doesnt-need-data) - How DuckDB can provide a view over data stored in S3.
* [Securing DuckDB, Improving Startup Time, and Working Offline](https://blog.colinbreck.com/securing-duckdb-improving-startup-time-and-working-offline/) - How to set up DuckDB and how to work with extensions in an offline (and potentially sensitive) environment.
* [Datalore 2025.2 Is Out With Report Tabs, Extended DuckDB Support, and Snowflake Key Pair Authentication](https://blog.jetbrains.com/datalore/2025/04/17/datalore-2025-2-is-out-with-report-tabs-extended-duckdb-support-and-snowflake-key-pair-authentication-2/) - Improved DuckDB support in JetBrains' Datalore collaborative data science platform
* [Using DuckDB WASM + Cloudflare R2 to host and query big data (for almost free)](https://andrewpwheeler.com/2025/06/29/using-duckdb-wasm-cloudflare-r2-to-host-and-query-big-data-for-almost-free/) - Demo of using Cloudflare R2 hosting and a WASM DuckDB application to store and query data
* [SwanLake](https://www.wangfenjin.com/posts/swanlake-en/) - An Arrow Flight SQL Datalake Service Built on DuckDB + DuckLake
* [DuckDB-Wasm on a Plain Static Host — Without Breaking AdSense](https://csvtodashboard.com/duckdb-wasm-static-host) - Why a static site ships the single-threaded build: SharedArrayBuffer, COOP/COEP, and the cross-origin isolation tradeoff.
* [Building duckdb-pst](https://intellekt.fyi/2026/02/03/the-data-warehouse-in-your-email-archive-teaching-duckdb-to-speak-outlook/) - How to go from 0 to a production-ready DuckDB extension for Outlook PSTs, including table functions, MAPI schema serialization, projection/statistics pushdown, concurrent planning, and late materialization.

### Books

* [DuckDB in Action](https://www.manning.com/books/duckdb-in-action) - DuckDB in Action will show you how to quickly get your hands dirty with DuckDB.
* [Getting Started with DuckDB](https://www.packtpub.com/en-us/product/getting-started-with-duckdb-9781803241005) - A practical guide for accelerating your data science, data analytics, and data engineering workflows.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
