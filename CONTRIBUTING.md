# Contributing to the Project

Thank you for considering contributing to this project! Please follow these steps to get started:

---

## How to Contribute

1. **Open an Issue**:
    - If you encounter a bug or have a suggestion, open an issue on GitHub.

2. **Fork the Repository**:
    - Click "Fork" at the top of the repository page.

3. **Create a Branch for Your Work**:
    - Name the branch something relevant (e.g., `fix-bug-x`, `add-new-feature`):
      ```bash
      git checkout -b my-branch
      ```

4. **Follow Code Guidelines**:
    - Write clean, well-documented, and testable code.
    - Ensure that your changes align with the project's conventions.

5. **Commit Your Work Using Conventional Commits**:
    - Follow the [Conventional Commits](https://www.conventionalcommits.org/) standard to structure your commit messages. This ensures commits are descriptive, clear, and can be used to automate versioning and changelogs.
    - Commit message structure:
      ```
      <type>[optional scope]: <description>
 
      [optional body]
 
      [optional footer(s)]
      ```
    - Examples:
        - For a bug fix:
          ```
          fix: correct null pointer in user login function
          ```
        - For a new feature:
          ```
          feat(search): add DFS algorithm implementation
          ```
        - For a breaking change:
          ```
          fix(auth): modify token expiration logic
   
          BREAKING CHANGE: tokens are now invalidated after 24 hours
          ```

6. **Run Tests**:
    - Ensure all tests pass or, if applicable, provide new/fixed tests for the changes made.

7. **Submit Your Changes**:
    - Push your branch:
      ```bash
      git push origin my-branch
      ```
    - Open a Pull Request (PR) and ensure you provide a clear description of what your contribution achieves.

---

## Code Style Guidelines

This project adheres to the following conventions:
- Use meaningful names for variables, functions, commits, and pull requests.
- Keep your code clean and properly documented.
- Ensure consistency with existing code and follow the coding style used in the project.

---

## Commit Message Types (Conventional Commits Guidelines)

Here is a list of commonly used types in commit messages under the Conventional Commits standard:

- **feat**: A new feature.
- **fix**: A bug fix.
- **docs**: Documentation-only changes.
- **style**: Changes that do not affect the code’s logic (e.g., formatting, white-space).
- **refactor**: Code changes that neither fix a bug nor add a feature.
- **perf**: Code changes that improve performance.
- **test**: Adding missing tests or correcting existing tests.
- **chore**: Changes to the build process or auxiliary tools, library upgrades, etc.

For more detailed information, visit the [Conventional Commits Specification](https://www.conventionalcommits.org/).

---

## Contact

Feel free to contact us by opening an issue or via email: `leandro.franchi@gmail.com`.