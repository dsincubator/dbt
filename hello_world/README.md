# hello_world

The goal of this project is is to build a hello_workd/ project with `dbt-core`.

I'm looking for this properties:

* Open source.
* Free.
* Easy to install.
* Easy to see what's crucial.
* Can run in a container (not in my precious sytem).
* Can run in isolation (e.g. I don't need a remote database).
* No need for secrets.

### Stuggles

* As someone who has learned many technologies, I'm surprised and frustrated that it took me 2 days to get build a "hello world" project with the properties I list above.

* The dbt documentation confused me, starting with the prominent advertising for dbt cloud (which I don't want) and the obsure mention of `dbt-core` (which I want).

* Most "quickstart" projects assume you already have a data warehouse and the credentials to set it up. After trying multiple database adaptors I realized that duckdb can be used with no configutation (like sqlite but with lots' of power). 

* This project got me started: [this one](https://github.com/dbt-labs/jaffle_shop_duckdb).

* `dbt init` populates the dbt project with way too much stuff for a biginner to notice what is crucial versus "nice to have". ChatGTP helped me arrive to the "hello_world" project in this repo. I avoided `init` and build the project by hand. Done that ways it's easy to see the number of minimal componets is small.

* A good playground is GitHub codespaces, and maybe [VS Code with dev-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) in the backend.

