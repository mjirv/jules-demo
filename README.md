# Jules

Jules is a SQL-based data transformation package.

It allows you to create templated SQL using Python and execute it against your data warehouse to create analytics tables. 

## Usage
Jules has three components:
1. **Functions** - reusable SQL snippets; see `functions/`
2. **Transforms** - files with a `transform()` function that returns a SQL select statement; see `transforms/`
3. **Projects** - the DAG of Jules. A series of transforms to run against your database; see `project.py`