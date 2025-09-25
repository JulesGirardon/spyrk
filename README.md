# Spyrk

Spyrk is a Python project designed to facilitate modern development workflows, automation, and Test-Driven Development (TDD).

---

## 🚀 Quick Start

1. **Clone the repository**

   ```bash
   git clone git@github.com:JulesGirardon/spyrk.git
   cd spyrk
   ```

2. **Install dependencies and set up the environment**

   ```bash
   ./install
   ```
---

## 🛠️ Requirements

- Python 3.12 or higher
- [uv](https://github.com/astral-sh/uv) (for fast dependency management)
- Git

---

## 📂 Project Structure

- `bin/` : Automation scripts for development, testing, linting, type checking, documentation, and cache clearing.
- `src/` : Main source code.
- `tests/` : Unit and integration tests.
- `docs/` : Sphinx documentation.
- `.venv/` : Virtual environment (created automatically).
- `pyproject.toml` : Project configuration and dependencies.

---

## ⚡ Main Commands

All automation scripts are in the `bin/` directory.  
Run them from the project root (with the virtual environment activated):

| Script       | Description                                                  |
| ------------ | ------------------------------------------------------------ |
| `install`    | Install all dependencies (dev, lint, tests…)                 |
| `codecheck`  | Run type checks (mypy), lint (ruff), and tests with coverage |
| `mypycheck`  | Run type checking with mypy                                  |
| `ruffcheck`  | Lint and auto-fix code with Ruff                             |
| `tests`      | Run tests with coverage (HTML report)                        |
| `make_doc`   | Generate documentation with Sphinx                           |
| `clearcache` | Remove all Python cache files and folders                    |

Example usage:

```bash
./bin/codecheck
./bin/tests
./bin/make_doc
./bin/clearcache
```

---

## 🧪 Testing

- Tests are in the `tests/` directory.
- Run all tests with coverage:
  ```bash
  ./bin/tests
  ```
- Coverage HTML report is generated in `htmlcov`.

---

## 📚 Documentation

- Documentation is generated with Sphinx.
- To build the docs:
  ```bash
  ./bin/make_doc
  ```
- Output is in `docs/build/html`.

---

## 🧹 Cache Cleaning

Remove all Python cache files and folders:

```bash
./bin/clearcache
```

---

## 🏆 Quality Tools

- **Type Checking**: mypy (`./bin/mypycheck`)
- **Linting & Auto-fix**: Ruff (`./bin/ruffcheck`)
- **Testing & Coverage**: pytest (`./bin/tests`)
- **Documentation**: Sphinx (`./bin/make_doc`)

---

## 💡 Recommended Workflow

1. Install dependencies: `./install`
2. Check code quality: `./bin/codecheck`
3. Run tests: `./bin/tests`
4. Generate docs: `./bin/make_doc`
5. Clean cache: `./bin/clearcache`

---
