# src

This folder contains the source code for the project.

## Purpose

The `src` package holds the application's core code. Keeping it as a
dedicated package (with an `__init__.py`) allows the code to be imported
as a module and keeps the project root clean of implementation details.

## Structure

- `__init__.py` — marks this directory as a Python package.
- `main.py` — entry point / placeholder for the package's code.

## Conventions for contributors

- Add new modules directly under `src/` unless a subpackage is warranted.
- Keep `__init__.py` files minimal; avoid adding logic there.
- Follow standard Python style (PEP 8) for any code added to this package.
- Update this README when the structure or purpose of the package changes.
