# Readme for ctdcloud
Set up venv:

    uv venv --python=3.12

sete up mkdocs:

    uv pip install mkdocs mkdocs-material 

In root of project:

    mkdocs new .

Create pyproject.toml

`uv lock` will create lockfile.

(uv synch will install stuff)

Usage: 
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

Serving it at readthedocs:


