# Structure

Explore a minimal, "hello_world" dbt project and notice how it changes as you run basic commands.

* `profiles.yml` defines the connection to your database. 
* `dbt_project.yml` is the main configuration file for a dbt project.
* `models/` contains each .sql file that defines the SLQ transformations that yield a table or view in your database.

```bash
dbt run

git status
git commit -m "run"
```


```bash
dbt test

git status
git commit -m "test"
```

```bash
dbt docs generate

git status
git commit -m "docs generate"
```

```bash
dbt docs serve
```
