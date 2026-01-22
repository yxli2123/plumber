# plumber

plumber is a project for synthesizing post-training data: prompt inputs and
their corresponding verifiers.

## Installation

Prerequisites:
- Python 3.12+
- `uv` (https://github.com/astral-sh/uv)

Create the virtual environment and install dependencies:

```
uv sync --dev
```

## Project structure

- `docs/` — documentation and design notes
- `data/` — local datasets (ignored or kept minimal)
- `examples/` — example prompts/verifiers and usage samples
- `scripts/` — helper scripts for data generation and validation
- `tests/` — test suite
- `src/` — package source code

## Documentation

Docs are generated from docstrings with MkDocs + mkdocstrings.

Preview locally:

```
uv run mkdocs serve
```