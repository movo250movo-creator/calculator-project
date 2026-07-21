# Calculator Project

A simple command-line calculator written in Python. It supports the four basic arithmetic operations and includes a packaged Windows executable for users who do not have Python installed.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Divide-by-zero protection
- Interactive menu that runs until you choose to exit
- Standalone Windows executable

## Run with Python

### Requirements

- Python 3

Clone the repository and run:

```bash
git clone https://github.com/movo250movo-creator/calculator-project.git
cd calculator-project
python calculator.py
```

On Windows, you can also use:

```powershell
py calculator.py
```

## Run the Windows executable

Download or clone the repository, then launch:

```text
dist/calculator.exe
```

The executable runs in a terminal window and does not require a separate Python installation.

## Usage

Choose an operation from the menu, enter two numbers, and the calculator will display the result.

```text
=== Simple Python Calculator ===

Choose an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
```

## Build the executable

The included `calculator.spec` file can be used with PyInstaller:

```bash
pip install pyinstaller
pyinstaller calculator.spec
```

The generated executable will be placed in the `dist` directory.

## Project structure

```text
calculator-project/
|-- calculator.py
|-- calculator.spec
|-- dist/
|   `-- calculator.exe
`-- README.md
```
