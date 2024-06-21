# Overview

Overview what is `dbt`, why and when it's useful, and how to use it.

## What is `dbt`?

* `dbt` means data build tool.
* It's open-source software.
* Runs in the terminal.

## Why it's useful?

`dbt` (data build tool) makes your data pipelines more efficient and reliable:

* It helps you to transform, test, and document data. 
* It encourages best practices from software engineering, e.g. version control, CI/CD.

## When it's most useful

* When you need to transform raw data in your data warehouse into a more usable state for analysis.

## When it's not so useful

* When your data transformation is simple, and doesn't need to scale.
* When your team isn't comfortable with SQL or command-line interfaces.
* When your data is not stored in a SQL-based data warehouse.

## How to use it

If you're using (not building) the `dbt` project, these commands should be enough:

1. Execute transformations.

   ```bash
   dbt run
   ```

2. Validate the integrity of the transformed data.

   ```bash
   dbt test
   ```

3. Generate and access the documentation.

   ```bash
   dbt docs generate
   dbt docs serve
   ```
