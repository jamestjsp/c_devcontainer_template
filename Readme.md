# C/CXX devcontainer Template Repo

Welcome to the C/CXX devcontainer Template Repo! This repository serves as a starting point for creating new development containers for C/CXX projects.

## Getting Started

To get started with this template, follow these steps:

1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/jamestjsp/c_devcontainer_template.git
   ```
2. Copy the `.devcontainer` directory to the root of your project.
   ```sh
   cp -r c_devcontainer_template/.devcontainer your-project-root/
   ```
3. Open your project in Visual Studio Code.
   ```sh
   code your-project-root
   ```
4. Install the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension in Visual Studio Code.
5. Reopen the project in the container:
   - Press `F1` and select `Remote-Containers: Reopen in Container`.
   - VS Code will build and start the development container based on the configuration in the `.devcontainer` directory.
6. Once the container is running, you can start coding and debugging within the containerized environment.

## Features

This template repo includes the following features:

- Pre-configured development environment for C/CXX projects.
- Docker-based development container for consistent and reproducible development environments.
- Easy customization of devcontainer configuration files.
- Integration with popular code editors and IDEs.

## VS Code Setup

To set up your development environment in Visual Studio Code, follow these steps:

1. Install the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.
2. Open your project in VS Code.
3. Press `F1` and select `Remote-Containers: Reopen in Container`.
4. VS Code will build and start the development container based on the configuration in the `.devcontainer` directory.
5. Once the container is running, you can start coding and debugging within the containerized environment.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This template repo is licensed under the [MIT License](LICENSE).