# 🍪 Cookiecutter Template for Python Package

This Cookiecutter template provides a standardized structure for creating Python packages. It's designed to streamline the initial setup process and promote best practices for package development.

## 🤖 Features

- Standard repo structure
- Documentation with [mkdocs](https://www.mkdocs.org) with [Material theme](https://squidfunk.github.io/mkdocs-material/)
- Test with [pytest](https://docs.pytest.org/en/8.0.x/)
- Coverage control with [pytest-cov](https://pytest-cov.readthedocs.io/en/latest/)
- CI/CD with Github Workflows, includes default actions for building, testing, publishing the package.
- CLI example with [Typer](https://typer.tiangolo.com)

Optional dev tools:

- Code Formatting with [Black formatter](https://black.readthedocs.io/en/stable/)
- Dependencies and import cleaning with [isort](https://pycqa.github.io/isort/)

The template supports Python 3.12.

## 🧪 Requirements

- Python 3.12 or higher
- Cookiecutter

## 👾 Usage

1. Install Cookiecutter if you haven't already:

    ```bash
    pip install cookiecutter
    ```

2. Generate a new Python package project using this template:

    ```bash
    cookiecutter gh:LouisStefanuto/cookiecutter-python
    ```

   1. Replace your_username with your GitHub username.
   2. Follow the prompts to provide information about your package, such as its name, description, author, etc.
   3. After filling out the prompts, the template will generate a new directory with your package files based on the provided information.
   4. Navigate to the generated directory and start developing your Python package!

## 👋 Contributing

If you encounter any issues with the template or have suggestions for improvements, feel free to open an issue or submit a pull request on the GitHub repository.
