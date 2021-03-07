Python Simple Project
=====================

Basic project based on the series or articles:

* [How to start a Python project with Django in 2020](https://medium.com/@cristobalcl/how-to-start-a-python-project-with-django-in-2020-803122721b23?sk=f8989aec603e1e8d40ffc3d3dd7e4b50)
* [Set up tests, linters and type checking in Python projects in 2020](https://medium.com/@cristobalcl/set-up-tests-linters-and-type-checking-in-python-projects-in-2020-9cc1b1e2750d)

but without Django.

Dependencies
------------

Project dependencies:

* [pyenv](https://github.com/pyenv/pyenv#installation)
* [Poetry](https://python-poetry.org/docs/#installation)
* [nox](https://nox.thea.codes)

Cookiecutter install:

```
pip install cookiecutter
```

Usage
-----

Create project:

```
cookiecutter https://github.com/cristobalcl/cookiecutter-py-simple-project
```

Then:

```
cd [project_slug]
git init
poetry install
poetry run pre-commit install
```

Run test suite with `nox`. To reuse previous environment use `nox -r`.

Maybe you'll want to delete, rename, move, and/or edit `[project_slug]/tests/test_[project_slug].py` before your first commit.
