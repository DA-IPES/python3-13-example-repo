# python3-13-example-repo

Before reading this guide, be sure that [uv](https://docs.astral.sh/uv/getting-started/installation/) is installed on your system.

To set up the environment, download a copy of this repository, open a terminal at the root of the project, then run: 

```
uv sync
```

This will install the proper Python version and all libraries on your system. 

To run a Python file containing your program: 

```
uv run python <path-to-file>

# example (!!! on Windows, use "\" instead of "/" in paths)
uv run python ./src/python3_13_example_repo/main.py

# output : Hello World 
```
