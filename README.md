# scoop-zpace

A [Scoop](https://scoop.sh) bucket for [Zpace](https://github.com/AzisK/Zpace) - a CLI tool to discover what's hogging your disk space.

## Installation

First, add this bucket to Scoop:

```powershell
scoop bucket add zpace https://github.com/AzisK/scoop-zpace
```

Then install Zpace:

```powershell
scoop install zpace
```

## Usage

```powershell
# Scan your home directory (default)
zpace

# Scan a specific directory
zpace C:\Users\YourName\Documents

# Show top 20 items per category
zpace -n 20
```

## Requirements

- [Scoop](https://scoop.sh) package manager
- Python (will be installed as a dependency if not present)

## Update

```powershell
scoop update zpace
```

## Uninstall

```powershell
scoop uninstall zpace
```

## Alternative Installation

If you prefer using [uv](https://github.com/astral-sh/uv) directly (faster):

```powershell
uv tool install zpace
```

Or with pip:

```powershell
pip install zpace
```

## About Zpace

Zpace is a CLI tool that helps you identify:
- 📊 Large files grouped by type (Documents, Videos, Code, Pictures, etc.)
- 📦 Space-hungry directories like node_modules, Python virtual environments, and build artifacts
- 🎯 Actionable insights to help you quickly free up space

For more information, visit the [Zpace repository](https://github.com/AzisK/Zpace).
