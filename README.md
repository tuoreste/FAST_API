# Setting Up Python Environment in Visual Studio Code

This repository contains instructions for setting up a Python development environment in Visual Studio Code (VSCode) on macOS. This environment includes Python 3.9 and FastAPI for building web applications.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Homebrew](https://brew.sh/) (for macOS package management)
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)
- [Python 3.9](https://www.python.org/downloads/release/python-394/) (installed via Homebrew)

## Steps

### 1. Install Python (on macOS)

```shell
brew install python
```

This command will use Homebrew to install Python 3.9 on your macOS system.

### 2. Create a Python Virtual Environment

Navigate to the directory where you want to create your Python project, and then run the following command to create a Python virtual environment named `myenv`:

```shell
python3.9 -m venv myenv
```

This will create a virtual environment with Python 3.9 in a folder named `myenv` in your project directory.

### 3. Activate the Virtual Environment

You need to activate your virtual environment every time you open VSCode. Run the following command to activate it:

```shell
source myenv/bin/activate
```

You will see your terminal prompt change, indicating that the virtual environment is active.

### 4. Install FastAPI and Uvicorn

With your virtual environment active, you can install FastAPI and Uvicorn using `pip`:

```shell
pip install fastapi uvicorn
```

This will install FastAPI and Uvicorn within your virtual environment, ensuring that your project has the necessary dependencies.

## Usage

Now you have a Python environment set up in VSCode, complete with FastAPI for building web applications. You can start coding your Python projects with these tools.

Remember to activate your virtual environment (`source myenv/bin/activate`) whenever you work on your Python projects in VSCode to ensure that you are using the correct Python interpreter and dependencies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thank you to the open-source community for providing these essential tools for Python development.