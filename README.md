# optibot-test-python-api

Test repository for OptiBot parallelize detection.

Simulates a Python API project with:
- 3 independent steps: lint (ruff), type check (mypy), unit tests
- 3 dependent steps: start database → run migrations → integration tests

Expected OptiBot behavior: detect that lint, type check, and unit tests can run in parallel, while the database chain must stay sequential.
# Run 1
# Run 2
# Run 3
# Run 4
# Run 5
