<h1 align="center">🛡️ CryptoHack Solutions</h1>

This repository contains the solutions I found for the challenges on [CryptoHack](https://cryptohack.org), a platform for learning cryptography through hands-on problem solving.

## 📂 Structure

Solutions are organized by category, following the structure of the website. Each folder or file corresponds to a solved challenge.

## ⚠️ Disclaimer

These solutions reflect my personal understanding of the challenges. I highly recommend trying to solve them on your own before checking the answers!

## 📔 Venv

This quick guide will help you set up an isolated Python virtual environment for this project and install the necessary dependencies using the `requirements.txt` file.

## Prerequisites

* **Python installed:** Ensure that Python is installed on your machine. You can check the installation by opening your terminal or command prompt and typing:
    ```bash
    python --version
    ```
    or
    ```bash
    python3 --version
    ```
* **Pip installed:** Pip is the package installer for Python and usually comes bundled with recent Python versions. Verify its installation by typing:
    ```bash
    pip --version
    ```
    or
    ```bash
    pip3 --version
    ```

## Creating a Virtual Environment

A virtual environment isolates this project's dependencies from other Python installations on your system, preventing version conflicts.

1.  **Open your terminal or command prompt.** Navigate to the root directory of your project (where the `requirements.txt` file is located).

2.  **Create the virtual environment:** Run the following command to create a new virtual environment named `venv`:
    ```bash
    python -m venv venv
    ```
    This command will create a folder named `venv` within your project directory, containing a copy of the Python interpreter and package management tools.

## Activating the Virtual Environment

Before installing the dependencies, you need to activate the virtual environment. The activation command varies depending on your operating system:

* **On Windows (using PowerShell):**
    ```powershell
    .\venv\Scripts\Activate.ps1
    ```
* **On Windows (using Command Prompt - cmd):**
    ```bash
    .\venv\Scripts\activate.bat
    ```
* **On macOS and Linux:**
    ```bash
    source venv/bin/activate
    ```

    Upon activation, you will see the name of the virtual environment (`(venv)`) at the beginning of your terminal or command prompt line, indicating that the virtual environment is active.

## Installing Dependencies

The `requirements.txt` file lists all the Python libraries required for this project and their respective versions.

1.  **Ensure that the virtual environment is active** (the `(venv)` should be visible in your terminal).

2.  **Install the dependencies:** Run the following command to install all the libraries listed in `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
    This command will download and install all the necessary dependencies within your virtual environment.

## Next Steps

With the virtual environment set up and the dependencies installed, you can now run the code for this project without worrying about version conflicts with other Python installations on your system.

**To deactivate the virtual environment** when you are finished working on the project, simply run the following command in your terminal:

```bash
deactivate