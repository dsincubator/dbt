# dbt

Learnig dbt from scratch.

When I learn something new I look for this properties:

* Open source
* Free
* Easy to install.
* Easy to see what's crucial.
* Can run in a container (not in my precious sytem).
* Can run in isolation (e.g. I don't need a remote database).
* No need for secrets.

### Stuggling to build hello_world/

As someone who has learned many technologies, I'm surprised it took me 2 days to get build a 
"hello world" project with the properties I list above.

The dbt documentation confused me, starting with the prominent advertising for dbt cloud (which I don't
want) and the obsure mention of `dbt-core` (which I want).

1. Most "quickstart" projects assume you already have a data warehouse and the credentials to set it up. 
It took me a long while to realize that DuckDB can be used without configutation. Only then I could get
something to work. The project that eventually got me sarted is
[this one](https://github.com/dbt-labs/jaffle_shop_duckdb).

1. Calling `dbt init` populates the dbt project with way too much stuff for a biginner to notice what is
crucial versus "nice to have". ChatGTP helped me arrive to the "hello_world" project in this repo.

1. One good computing environment to try this out is GitHub codespaces. This way you can keep your own
system untouched.

