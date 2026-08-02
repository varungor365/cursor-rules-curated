# Python & FastAPI Rules

When working in this Python repository, follow these rules:

1. **Typing:** Use absolute strict typing for every function and class. Use `mypy` compatible syntax.
2. **Frameworks:** Prefer standard library where possible. For APIs, strictly use `FastAPI` and `Pydantic` v2.
3. **Async:** All I/O operations must be `async`. Use `httpx` instead of `requests`.
4. **Code Style:** Follow `black` formatting and `ruff` linting rules. No exceptions.
5. **Testing:** Write tests using `pytest`. Mock external services using `unittest.mock`.
