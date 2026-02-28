# claude-lab

A sandbox for experimenting with the [Anthropic Python SDK](https://github.com/anthropics/anthropic-sdk-python).

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install anthropic python-dotenv
```

Create a `.env` file with your API key:

```
ANTHROPIC_API_KEY=your_key_here
```

## Dev tools

```bash
.venv/bin/pytest          # run tests
.venv/bin/black .         # format
.venv/bin/ruff check .    # lint
.venv/bin/mypy .          # type check
```
