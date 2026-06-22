# OpenICU Project Template

This is a template for creating OpenICU projects. It includes a basic project structure, configuration files, and setup scripts to help you get started quickly.

## Features

- 📁 Pre-configured with [uv](https://docs.astral.sh/uv/) for dependency management.
- 🪛 Linting with [ruff](https://docs.astral.sh/ruff/).
- 🔧 Type checking with [ty](https://docs.astral.sh/ty/).
- 📝 [Pre-commit](https://pre-commit.com/) hooks for code quality.
- 📦 Uses [dev container](https://containers.dev/) development setup.
- 🧰 Integrated with [GitHub](https://docs.github.com/en) Actions for CI/CD automation and other workflows.

## Getting Started

> [!NOTE]
> Use the included dev container to automatically install all the necessary dev tools and dependencies. To use this you first need to install docker under Linux or WSL2 under windows.

1. **Clone the repository:**
    ```sh
    git clone https://github.com/aidh-ms/openicu-project-template
    cd openicu-project-template
    ```

2. **Open the project in Visual Studio Code:**
    ```sh
    code .
    ```

3. **Reopen in container:**
    - Press `F1` to open the command palette.
    - Type `Remote-Containers: Reopen in Container` and select it.
    - VS Code will build the Docker container defined in the `.devcontainer` folder and open the project inside the container.

## Documentation

Some documentation description

### Additional features

* [Dev Container Feature](https://containers.dev/features)
