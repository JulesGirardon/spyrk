# Spyrk

Spyrk is a Python project designed to facilitate development and TDD practice.

# Installation

```bash
git clone git@github.com:JulesGirardon/spyrk.git
cd spyrk
./install
```

## Requirements

- Python 3.9 or higher
- Git

## Activate the environment

```bash
source .venv/bin/activate
```

## Commands

Here are the available commands in the `bin` directory:

- `bin/clearcache`: Clear the application cache.
- `bin/tests`: Run all tests.
- `bin/typecheck`: Perform type checking using mypy.
- `bin/flakecheck`: Check code style using flake8.
- `bin/importcheck`: Verify import order using isort.
- `bin/formatcheck`: Check code formatting.

## Unit Tests

Unit tests follow the principles of Test-Driven Development (TDD).

```bash
pytest
```

## Quality

Some interesting indicators:

- mypy for type checking
- pytest for tests and coverage
- flake8 for code style
- isort for imports

Quick check with:

```bash
./codecheck
```

Check tests and coverage with:

```bash
pytest --cov=src --cov-report=html
```
