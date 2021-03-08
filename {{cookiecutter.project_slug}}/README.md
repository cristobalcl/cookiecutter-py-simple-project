# {{cookiecutter.project_name}}

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

Dependencies
------------

* [pyenv](https://github.com/pyenv/pyenv#installation)
* [Poetry](https://python-poetry.org/docs/#installation)
* [nox](https://nox.thea.codes)

Development
-----------

To install the Python version:

```
pyenv install 3.8.2
```

After cloning the repository run:

```
poetry install
poetry run pre-commit install
```
