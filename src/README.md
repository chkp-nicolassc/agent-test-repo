# src

This folder contains the source code for the project.

## Purpose

The `src` package holds the application's core code. Keeping it as a
dedicated package (with an `__init__.py`) allows the code to be imported
as a module and keeps the project root clean of implementation details.

## Structure

- `__init__.py` — marks this directory as a Python package.
- `main.py` — entry point / placeholder for the package's code.

## Setup notes

- No external dependencies are required to import this package.
- To run the entry point locally, execute it as a module from the project
  root, e.g. `python -m src.main`.
- If dependencies are introduced later, document how to install them here
  (e.g. `pip install -r requirements.txt`) and note any required
  environment variables or configuration files.

## Testing

- No test suite exists for this package yet. When adding tests, place them
  under a top-level `tests/` directory (e.g. `tests/test_main.py`) mirroring
  the module layout in `src/`.
- Prefer `pytest` for new tests unless the project standardizes on another
  framework, and document the test command here once one is chosen
  (e.g. `pytest tests/`).

## Conventions for contributors

- Add new modules directly under `src/` unless a subpackage is warranted.
- Keep `__init__.py` files minimal; avoid adding logic there.
- Follow standard Python style (PEP 8) for any code added to this package.
- Update this README when the structure or purpose of the package changes.

## See also

- [Project root README](../README.md) for general project information.
