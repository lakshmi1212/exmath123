# exmath123

This repository provides basic math operations (addition, subtraction) with production-ready Python code and pytest-based test coverage.

## Folder Structure

- `src/`: Source code for math operations
- `tests/`: Pytest-based unit tests
- `default/`: Project metadata, requirements, and documentation

## Usage

Install dependencies:

```bash
pip install -r default/requirements.txt
```

Run all tests:

```bash
pytest tests/
```

## CI/CD

A GitHub Actions workflow (`.github/workflows/ci.yml`) is expected to run all tests on push and PR events.

## Math Operations

```
from src.math_operations import add, subtract
print(add(2, 3))       # 5
print(subtract(5, 2))  # 3
```
