## uv – Fast Python Package Manager

`uv` is a super fast Python package manager built as a replacement for `pip` and `virtualenv`. It's written in Rust and is designed to be much faster while still being easy to use.

## Installation

**For macOS / Linux:**

```bash
curl -Ls https://astral.sh/uv/install.sh | bash
```

**For Windows (PowerShell):**

```powershell
irm https://astral.sh/uv/install.ps1 | iex
```

After installing, restart your terminal

## How to Use

Create a virtual environment:

```bash
uv venv
```
Packaged applications Many use-cases require a package. For example, if you are creating a command-line interface that will be published to PyPI or if you want to define tests in a dedicated directory.

The --package flag can be used to create a packaged application:

```powershell
uv init --package example-pkg
```
And to install packages in project

To add a dependency:
```powershell
uv add openai_agents
```
