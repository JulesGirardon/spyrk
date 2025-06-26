# Spyrk

Spyrk est un projet Python conçu pour faciliter le développement et les tests.

# Installation

```bash
git clone git@github.com:JulesGirardon/spyrk.git
cd spyrk
./install
```

## Prérequis

- Python 3.9 ou supérieur
- Git

## Activer l'environnement 

```bash
source .venv/bin/activate
```

## Tests unitaires

Les tests unitaires suivent les principes du développement piloté par les tests (TDD).

```bash
pytest
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
