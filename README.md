# Fitfixer

## 

## Introduction

Currently, FIT files recorded by Tymewear experience two little issues:

1. Power is recorded in a custom field "tymewear power" wheres the standard field "power" remains unset.
2. Cadence is recorded as half the value.

The Fitfixer tool fixes these issues.

## Install requirements

Fitfixer is distributed as a Python package. Several installation methods are available.

### Using pip

Executing `pip` installs the package in your current Python environment. Global installation was once possible, but
modern Linux distributions no longer permit this approach.

```bash
pip install fitfix
```

### Using pipx or uv

Both `pipx` and `uv` enable global tool installation. The package can be installed as follows:

```bash
pipx install fitfix
```

or

```bash
uv tool install fitfix
```

## How to use

```bash
fitfix <input file> <output file>
```
