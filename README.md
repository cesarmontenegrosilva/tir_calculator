# tir_calculator
Repository for the tir_calculator package. It is a python package that provides a simple interface to calculate the Internal Return Rate of a project  on a list of cashflows.

# TIR Calculator

[![PyPI Version](https://img.shields.io/pypi/v/tir_calculator.svg)](https://pypi.org/project/tir_calculator/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/your-username/tir_calculator/blob/main/LICENSE)

## Description

The TIR Calculator is a Python package that provides a simple interface to calculate the Internal Rate of Return (IRR) of a project based on a list of cashflows.

## Installation

You can install the package via pip:

pip install tir_calculator

## Usage

To calculate the IRR, use the `calculate_tir()` function provided by the package. Pass a list of cashflows as the argument, where positive values represent inflows and negative values represent outflows.

```python
from tir_calculator import calculate_tir

cashflows = [-1000, 500, 300, 200, 100]  # Example cashflows
tir = calculate_tir(cashflows)
print("TIR:", tir)
