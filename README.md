# fivethirtyeight-datasette

Dockerfile + scripts to pull CSVs from https://github.com/fivethirtyeight/data
and build those into a SQLite database, then generate appropriate metadata from
the FiveThirtyEight README files and serve the results using Datasette.

* https://github.com/simonw/csvs-to-sqlite
* https://github.com/simonw/datasette

Deployed to https://fivethirtyeight.datasettes.com/
