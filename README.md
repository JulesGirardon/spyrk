# Spyrk

Spyrk est un projet Python conçu pour faciliter le développement et les tests.

# Installation

```bash
git clone <repository-url>
cd spyrk
./install --profile devlocal
```

# Contribuer à Spyrk

## Prérequis

- Python 3.9 ou supérieur
- Git

## Tests unitaires

Les tests unitaires suivent les principes du développement piloté par les tests (TDD).

```bash
pytest tests/unit
```

## Qualité

Quelques indicateurs intéressants :

- mypy pour la vérification des types
- pytest pour les tests et la couverture des tests
- flake8 pour le style de code
- isort pour les imports

Vérification rapide avec :

```bash
./codecheck
```

Vérifiez les tests et la couverture des tests avec :

```bash
pytest --cov=src --cov-report=html
```
