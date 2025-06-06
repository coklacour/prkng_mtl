## Configuration guidelines

### Python environment

* to facilitate collaboration, I've integrated the Poetry tool. Poetry is a dependency management and packaging tool in Python. for more info https://python-poetry.org/docs/

* To install poetry, go to this web page : https://python-poetry.org/docs/#installation

* To activate and configure the Poetry environment, you need to run the 2 commands below.

```bash
poetry shell
poetry install
```

* It is important to run these commands at the start of each session 

### About the project structure

To start this magnificent project, I propose the following structure (https://drivendata.github.io/cookiecutter-data-science/):

    .
    ├── README.md          <- The top-level README for developers working on this project.
    ├── data
    │   ├── raw            <- Raw, unprocessed data.
    │   └── seeds          <- External or reference data used for seeding the project.
    │
    ├── docs               <- Documentation for project setup, development, or usage.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention uses a prefix number for ordering.
    │
    ├── reports            <- Generated analysis reports in HTML, PDF, LaTeX, etc.
    │
    ├── core               <- Private submodule used for managing key project data or logic.
    │   └── __init__.py    <- Makes `core` a Python module.

