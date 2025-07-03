# QR Code Generator

A simple Python command-line tool that generates QR codes from any text or URL. Uses the [`qrcode`](https://pypi.org/project/qrcode/) and [`Pillow`](https://pypi.org/project/Pillow/) libraries.

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [.gitignore](#gitignore)
- [License](#license)

---

## Features

- **Interactive CLI**
  Prompts you for the payload (text or URL) and the output filename.
- **Custom Styling**
  Configure box size, border width, foreground (`fill_color`) and background (`back_color`) colors.
- **Zero-config**
  No external configuration files—just install and run.

---

## Prerequisites

- Python 3.7+
- Git (for cloning the repository)

---

## Installation

1.  **Clone this repository**
    ```bash
    git clone https://github.com/NunoAraujo55/Qr-Code-Generator.git
    ```
2.  **Change into the project directory**
    ```bash
    cd Qr-Code-Generator
    ```
3.  **Create a virtual environment**
    ```bash
    python -m venv venv
    ```
4.  **Activate the virtual environment**

    To get your development environment up and running, you'll need to activate the virtual environment. This keeps your project's dependencies isolated from your system's global Python packages. Choose the command below that corresponds to your operating system:

    **macOS/Linux**
    ```bash
    source venv/bin/activate
    ```
    **Windows**
    ```bash
    .\venv\Scripts\activate.bat
    ```
5.  **Install the required dependencies**
    ```bash
    python -m pip install --upgrade pip
    python -m pip install qrcode pillow
    ```

## Usage
After installing the dependencies and activating your virtual environment, run the generator script:
```bash
$ python qr_code_generator.py
```
**You’ll be prompted to:**

- Enter the text or URL to encode.
- Provide an output filename (with the .jpg extension).
- Your QR code image will be saved in the project folder.

**Example**
```bash
Enter the text or URL to encode: https://example.com
Enter the output filename (without extension): my_qr_code.jpg
QR code generated and saved as my_qr_code.jpg
```
