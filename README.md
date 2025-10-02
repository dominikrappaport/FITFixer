# Fitfixer

## 

## Introduction

Currently, FIT files recorded by Tymewear experience two little issues:

1. Power is recorded in a custom field "tymewear power" wheres the standard field "power" remains unset.
2. Cadence is recorded as half the value.

The Fitfixer tool fixes these issues.

## Install requirements

Fitfixer uses a third-party library to process FIT files. To install it and all dependencies, please use this command:

```bash
pip install -r requirements.txt
```

## How to use

```bash
python fitfixer.py <input file> <output file>
```
