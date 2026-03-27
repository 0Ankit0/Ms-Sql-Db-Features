# MS SQL DB Features Notebook Collection

A curated knowledge base of SQL Server and ASP.NET snippets collected from real-world development scenarios.

## What this project contains

- Topic-focused Jupyter notebooks for SQL Server queries, schema patterns, JSON handling, and utilities.
- ASP.NET related notes for middleware, frontend setup, templates, and testing helpers.
- A Jupyter Book table of contents for structured navigation.

## How to use

1. Open any notebook to review a specific feature or pattern.
2. Read markdown explanation cells first, then run and adapt the example code.
3. Use `ProjectStructure.ipynb` for repository organization guidelines.

## Maintenance guidelines

- Keep an **Overview** markdown section at the top of each notebook.
- Add headings before major examples to explain intent and expected output.
- Update `_toc.yml` whenever notebooks are added or renamed.

## Build as a Jupyter Book (optional)

If you use Jupyter Book locally:

```bash
jupyter-book build .
```

This uses `_config.yml` and `_toc.yml` to generate a browsable documentation site.
