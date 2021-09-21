# SlapThatLikeButton-TestingStarterProject
A starter project to show how to set up and use automated testing in Python

![Tests](https://github.com/nprin/SlapThatLikeButton-TestingStarterProject/actions/workflows/tests.yml/badge.svg)


## Setup

To install the project in the virtual env with links to the src folder

```
pip install -e .
```

## Dev setup

```
pip install -r requirements_dev.txt
```

### Use of the tools mypy, flake8, pytest

mypy is used to check types coherence

```
mypy src
```

flake8 is a python code linter

```
flake8 src
```

Automated tests are done with pytest

```
pytest
```

tox is used to test on several python versions / platforms

**Important note** : this tool may take a long time.
All dependencies are reinstalled in specific folders.
And pytest, flake8 and mypy are relaunched.

```
tox
```

