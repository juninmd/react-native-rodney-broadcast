# AGENTS.md – Guidelines for AI Coding Agents

These guidelines are essential for ensuring the development and maintenance of the AGENTS.md repository. Adherence to these principles will promote a robust, maintainable, and scalable codebase.

**1. DRY (Don't Repeat Yourself)**

*   All code should have a single, clear purpose.
*   Avoid duplicating functionality across multiple files.
*   Refactor any duplicated code into a single, reusable module.
*   When implementing a common pattern, encapsulate it within a well-defined module.

**2. KISS (Keep It Simple, Stupid)**

*   Strive for simplicity in design and implementation.
*   Favor clear and concise code over overly complex solutions.
*   Minimize cognitive load for developers.
*   Avoid unnecessary abstractions or layers of complexity.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be required to depend on methods they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules; they should depend on abstractions.

**4. YAGNI (You Aren't Gonna Need It)**

*   Only implement functionality required for the immediate task or test case.
*   Avoid premature optimization; focus on essential implementation.
*   Refactor and simplify as needed, but don't add functionality that isn’t currently required.

**5. Code Structure & File Management**

*   Each file should contain a single, focused purpose.
*   File names should be descriptive and follow a consistent naming convention (e.g., `agent_module.py`).
*   Modules should be logically grouped and organized.
*   Consistent coding style (e.g., PEP 8 for Python, but adaptable) is essential.
*   Comments should explain *why* the code is doing something, not *what* it's doing (the code itself should be self-explanatory).
*   Use descriptive variable and function names.
*   Avoid overly long or complex functions.
*   Error handling should be minimal and focused on providing informative feedback.

**6. Testing & Coverage**

*   All development must be productive, not just for testing.
*   Unit tests should cover all core functionalities.
*   Aim for 80% test coverage.  Coverage reports should be available.
*   Test cases should be designed to cover edge cases and potential failure scenarios.
*   Test data should be realistic and representative of production data.
*   Use mocking library (e.g., `unittest.mock` or `pytest-mock`) consistently.

**7.  Code Generation Rules**

*   All code must be valid Python.
*   All function signatures must have type hints (e.g., `def my_function(arg1: int) -> int:`).
*   Variables must be defined before they are used.
*   Avoid global variables.  Use classes or modules to encapsulate state.
*   Line length should be generally limited to 180 lines.
*   Code should be well-formatted and readable.

**8.  Specific Considerations for AGENTS.md**

*   The file should contain the core logic for agent interaction, data processing, and reporting.
*   Focus on defining key agent behaviors and data models.
*   The code should be easily extensible to support new agent types or functionalities.
*   Include a clear README with instructions on how to set up and run the agents.

**9.  Maximum Code Length:** 180 lines.

**10.  AGENTS.md – Workflow**

*   Each change must be reviewed and approved by the team lead.
*   Code is tested before merging.
*   All testing must be automated.
*   Document all changes and rationale.

These guidelines are intended to promote a high-quality, maintainable, and scalable codebase for the AGENTS.md repository.  Regular code reviews and adherence to these principles will significantly contribute to the project’s long-term success.