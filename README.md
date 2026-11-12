<p align="center">
  <img src="https://img.shields.io/badge/WINDOWS_UTILITY-PYTHON_TO_EXE-101010?style=for-the-badge&labelColor=050805&color=00FF41" alt="Python to EXE Converter"/>
  <img src="https://img.shields.io/badge/BATCH-PYINSTALLER-101010?style=for-the-badge&logo=windows&logoColor=00FF41" alt="Windows Batch"/>
</p>

# Python to EXE Converter

Interactive Windows Batch utility for locating Python scripts and packaging them as executables with PyInstaller.

<p align="center">
  <a href="https://github.com/tzayadet/Shell-Batch/blob/main/docs/index.html"><strong>SHOWCASE SOURCE</strong></a> ·
  <a href="https://github.com/tzayadet/Shell-Batch"><strong>SOURCE CODE</strong></a>
</p>

[![GitHub Pages](https://github.com/tzayadet/Shell-Batch/actions/workflows/pages.yml/badge.svg)](https://github.com/tzayadet/Shell-Batch/actions/workflows/pages.yml)

## Features

- Checks whether Python is available.
- Checks for PyInstaller and installs it when required.
- Searches Desktop, Documents and Downloads.
- Accepts a custom path or direct file selection.
- Provides build options before compilation.
- Organises generated files in an output directory.
- Avoids overwriting existing executables through incremental filenames.
- Keeps build directories and temporary files inside the output folder; it does not delete `build` folders or `.spec` files from the source directory.

## Requirements

- Windows.
- Python installed and available in PATH.
- Internet access during PyInstaller installation, if it is not already installed.
- Pinned dependency in `requirements.txt` (PyInstaller 6.x).
- Sufficient permissions to install packages and write to the output directory.

## Usage

Run `Python2Exe_Converter.bat` from File Explorer or CMD and follow the menu.

## Technology

- Windows Batch
- Python
- pip
- PyInstaller

## Security

Package only scripts you own or whose origin you have verified. A packaged executable is not automatically signed or exempt from antivirus detection.

## Showcase and deployment

The [showcase source](docs/index.html) documents the Windows utility; it cannot run Batch scripts in a browser. GitHub Pages deployment is gated by the `ENABLE_PAGES=true` Actions variable.

## License

See [LICENSE](LICENSE).
