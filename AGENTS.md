```markdown
# AGENTS.md Guidelines

These guidelines outline the standards for development and coding practices for the AGENTS repository. Adherence to these principles is crucial for maintaining a well-structured, maintainable, and robust codebase.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data models, and API definitions must be encapsulated in reusable components or modules.
*   Avoid redundant code.
*   When a concept needs to be reused, implement it as a component with clear responsibilities.
*   When a functionality needs to be adapted, create a new component instead of modifying existing ones.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over unnecessary complexity.
*   Use simple and understandable code.
*   Minimize lines of code.
*   Break down complex tasks into smaller, manageable steps.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  Classes/modules should be open for extension but closed for modification.  Existing functionality should not be altered.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to implement interfaces they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.  Interfaces define low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Avoid adding features or code that is not currently required.
*   Implement functionality only when it's explicitly needed.
*   Refactor code to eliminate unnecessary complexity and potential future needs.
*   Focus on delivering working features first.

## 5. Code Structure & Organization

*   **File Size Limit:** Each file should not exceed 180 lines of code.
*   **Modular Design:** Organize code into logical modules and packages.  Each module should have a single, well-defined purpose.
*   **Naming Conventions:** Use consistent naming conventions throughout the codebase (e.g., camelCase for variables and functions, PascalCase for classes/modules).
*   **Comments:**  Provide clear and concise comments to explain complex logic, algorithm design, or non-obvious code.
*   **Documentation:**  Document API endpoints, data structures, and key algorithms to make code understandable.
*   **Error Handling:** Implement robust error handling and logging to provide informative error messages.

## 6. Testing

*   **Unit Tests:** All code must be thoroughly unit tested.
*   **Test Coverage:** Aim for at least 80% test coverage.
*   **Mocking/Stubbing:**  All mocks and stubs should be used *exclusively* for test purposes.  No real implementations are allowed.
*   **Test-Driven Development:**  Write tests before writing code.
*   **Test Case Design:**  Create test cases that cover all critical scenarios and edge cases.

## 7. Code Quality & Style

*   **Formatting:**  Follow a consistent code formatting style (e.g., black fork, whitespace). Use a code formatter (e.g., `black` in Python).
*   **Code Clarity:** Write code that is easy to read and understand.
*   **Readability:** Use meaningful variable names, clear indentation, and concise expressions.
*   **Avoidance of Magic Numbers:** Use constants for values that have a specific meaning.

## 8. Specific Considerations for AGENTS (Example - adaptable):

*   **Data Models:** Define data models clearly and concisely.
*   **API Design:**  Design APIs with well-defined contracts and error handling.
*   **Algorithms:**  Use efficient algorithms for common tasks.

## 9.  Development Workflow

*   **Version Control:**  Use Git for version control.
*   **Code Reviews:**  Conduct regular code reviews to ensure quality and consistency.
*   **Continuous Integration/Continuous Deployment (CI/CD):** Implement CI/CD pipeline for automated testing and building.

## 10.  Documentation Requirements

*   **README:** A clear README explaining the purpose of the AGENTS repository, how to install and run it, and how to contribute.
*   **API Documentation:**  Provide detailed API documentation using a tool like Swagger/OpenAPI.

These guidelines are a starting point and may be adjusted as the project evolves. Continuous refinement and adherence to these principles are vital for maintaining a high-quality and maintainable AGENTS repository.
```