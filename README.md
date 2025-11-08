## Overview

Automated text2sql system for generating and executing SQL queries on SQLite databases.

![image](https://github.com/user-attachments/assets/b6f5f98b-399b-4ae7-b72e-cff140133428)


Features:
* LLM-based schema linking
* Database content retrieval (basic)
* Retrieval of additional context (few-shot examples, database description) for better SQL generation.
* Execution-guided self-refinement to enforce syntax and result consistency

## Project structure
(TODO)

## Development

Setup:

```bash
git clone https://vixdang0x7d3/vitext2sql
uv sync
```

Interactive development with marimo notebooks:

```bash
uv run marimo edit notebooks/<file-name>.py
```

## Dependencies

- SQLGlot: SQL parsing and validation
- Marimo: Interactive notebooks for development and testing
- Pandas: Handling query result
- Transformers, OpenAI, LlamaCpp: Provide LLM access
