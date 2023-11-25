# DevContainer Boilerplate for LaTeX Resume

## Introduction
Welcome to `devcontainer-boilerplate-latex-resume`! This repository is designed to provide a quick and easy way to create a professional resume using LaTeX. It includes a development container configuration to streamline the setup process and ensure a consistent environment for LaTeX resume development.

## About the Resume Template
The resume template used in this boilerplate is `hipster-cv` template, created by [latex-ninja](https://github.com/latex-ninja) on [GitHub](https://github.com/latex-ninja/hipster-cv). This stylish and modern template is perfect for crafting a standout resume.

## About the Dev Container LaTeX Feature
The [LaTeX feature](https://github.com/prulloac/devcontainer-features/tree/main/src/latex) was released by [prulloac](https://github.com/prulloac), which includes [TeX Live](https://www.tug.org/texlive/) installation with latex compiler and tlmgr package manager. The feature also includes [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) extension for Visual Studio Code by [James-Yu](https://github.com/James-Yu).

## Prerequisites
Before you begin, ensure you have the following installed:
- [Docker](https://www.docker.com/get-started) (for running the development container)
- [Visual Studio Code](https://code.visualstudio.com/) (for local development)
- [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) for VS Code

## Using the DevContainer in Visual Studio Code
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Open in VS Code**: Open the cloned repository folder in Visual Studio Code.
3. **Reopen in Container**: When prompted, use the Remote-Containers extension to reopen the project inside the development container. Alternatively, you can use the Command Palette (`Ctrl+Shift+P`) and select "Remote-Containers: Reopen in Container".
4. **Edit Your Resume**: Once the container is running, you can start editing your resume in LaTeX. The main file is named `main.tex` (what a surprise!).
5. **Compile the LaTeX Document**: Use the LaTeX tools available in the container to compile your resume into a PDF.

## Using the DevContainer in GitHub Codespaces
1. **Open the Repository in GitHub**: Navigate to the repository on GitHub.
2. **Start a New Codespace**: Click the "Code" button and then "Open with Codespaces". Follow the prompts to create a new codespace.
3. **Edit and Compile**: Once the codespace is ready, you can edit your resume in LaTeX and compile it using the provided tools, just as you would in a local devcontainer setup.

## Customizing Your Resume
Feel free to modify the LaTeX files to suit your personal needs. The `hipster-cv` template is highly customizable, and you can adjust it to reflect your personal style and professional experience.

## Support and Contributions
If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Contributions to enhance this boilerplate are always welcome!

