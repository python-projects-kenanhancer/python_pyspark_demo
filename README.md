# python_pyspark_demo
PySpark demo

## Prerequisites

This project uses `asdf` for Python version management and `uv` as the package manager. Install them first:

### Install asdf

```bash
# macOS
brew install asdf

# Or using the official installer
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.0
echo '. "$HOME/.asdf/asdf.sh"' >> ~/.zshrc
echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.zshrc
```

### Install Python plugin for asdf

```bash
asdf plugin add python
```

### List available Python versions with asdf

`$ asdf list all python`

### Install Python runtime with asdf

`$ asdf install python 3.13.6`

### Select local Python runtime

`$ asdf set python 3.13.6`

## Install uv

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Create Virtual Environment and Install Dependencies

`$ uv sync`

## Activate Virtual Environment

`$ source .venv/bin/activate`

## Deactivate Virtual Environment

`$ deactivate`

## Remove Virtual Environment

`$ rm -rf .venv`