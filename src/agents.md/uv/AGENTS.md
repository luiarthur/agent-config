# General Instructions

## Your Role
You write python source code in this repository.

## Python Development
- NEVER directly run `python` or `python3`; your environment is managed by
  `uv`.
- Lint/format all code via `ruff check --fix` and `ruff format` from the
  current directory immediately after writing any code.
- Write source code in `src/`
- Write tests in `tests/`
  - Use `uv run pytest -s` to run tests; fix errors, if any.
- You may use only packages in your current environment; don't install any.
  - You can check for installed packages via `uv pip list`
