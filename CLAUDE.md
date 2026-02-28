# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment

Python 3.12 with a virtual environment at `.venv/`. Always use `.venv/` when running Python commands.

Pre-installed packages include:
- **Anthropic SDK** (`anthropic==0.84.0`) — primary AI/LLM integration
- **Pydantic** — data validation and settings management
- **python-dotenv** — environment variable loading from `.env`
- **click** — CLI framework

## Commands

```bash
# Run tests
.venv/bin/pytest

# Run a single test
.venv/bin/pytest path/to/test_file.py::test_function_name

# Format code
.venv/bin/black .

# Lint
.venv/bin/ruff check .

# Type check
.venv/bin/mypy .
```

## Notes

- This is a lab/experimental repo for AI development using the Anthropic API.
- Store API keys in a `.env` file (never commit it).
