# Python Best Practices Guide (2024)

*Date: 2026-03-24*

## Naming Conventions
- Use **snake_case** for functions, variables, and methods (e.g., `process_data`).
- Use **CamelCase** for class names (e.g., `DataProcessor`).
- Avoid ambiguous one‑letter names like `l`, `O`, or `I`; prefer descriptive names (`length`, `output`).
- Choose clear, descriptive identifiers rather than terse abbreviations (`multiply_by_two` vs `db`).

## Code Structure
- Keep lines under **79 characters**; break long statements using implicit line continuation inside parentheses.
- Separate top‑level functions and classes with **two blank lines**; methods inside classes with **one blank line**.
- Align continuation lines with the opening delimiter or use a **hanging indent** for readability.
- Prefer **four spaces** for indentation; never mix tabs and spaces.

## Error Handling
- Raise specific exceptions rather than generic `Exception` to convey intent.
- Use **try/except** blocks sparingly; handle only anticipated errors and let unexpected ones propagate.
- Include informative messages when re‑raising exceptions to aid debugging.
- Validate inputs early and fail fast with clear error messages.

## Documentation Practices
- Write **docstrings** for all public modules, classes, functions, and methods using triple quotes.
- Use a one‑line summary followed by a blank line and detailed description for complex objects.
- Keep comment lines **≤ 72 characters** and start with a capital letter.
- Prefer **block comments** for explaining sections of code; use **inline comments** only when the purpose is not obvious.
- Document arguments, return values, and raise sections in docstrings for clarity.

---
*Compiled from Python tutorial structure, PEP 8 guidelines, and recent best‑practice articles (2024).*
