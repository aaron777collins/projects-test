# msixrun

## 🔗 Quick Links

- [View on GitHub](https://github.com/aaron777collins/msixrun)

## 📊 Project Details

- **Primary Language:** Shell
- **Languages Used:** Shell
- **License:** MIT License
- **Created:** October 01, 2026
- **Last Updated:** October 01, 2026

## 📝 About

# msixrun

Install and launch an `.msix` / `.msixbundle` / `.appx` package from bash on Windows
(Git Bash, MSYS2 or WSL) with one command.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/aaron777collins/msixrun/main/install.sh | bash
```

Installs to `~/.local/bin/msixrun` (or `$PREFIX/bin`). Add that directory to your `PATH` if needed.

## Usage

```bash
msixrun path/to/app.msix            # install and launch
msixrun path/to/app.msixbundle --no-launch   # install only
msixrun

