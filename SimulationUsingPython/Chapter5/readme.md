# Chapter 5: Population Growth Simulation

This folder contains practice code and examples for Chapter 5 of Allen Downey's book *Modeling and Simulation in Python*, focusing on population growth models.

## Overview

Chapter 5 explores population dynamics using differential equations and simulation techniques. It covers:

- Exponential growth models
- Logistic growth models
- Implementing simulations with the ModSimPy library
- Analyzing population data and projections

## Files

- `PopulationGrowth.ipynb`: A Jupyter notebook implementing population growth simulations, including exponential and logistic models. It uses the ModSimPy library for modeling and simulation.

## Prerequisites

- Python 3.x
- Required libraries: NumPy, Matplotlib, SciPy, Pint (for units)
- ModSimPy library (downloaded automatically in the notebook)

Install dependencies if needed:
```bash
pip install numpy matplotlib scipy pint
```

## Setup and Running

1. Ensure dependencies are installed (see above).
2. Open `PopulationGrowth.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells in order. The notebook includes code to download ModSimPy if not present.
4. If you encounter `ModuleNotFoundError` for `scipy` or other libraries, install them as shown above.

## Notes

- The notebook uses physical units with the `pint` library.
- Simulations may require adjusting parameters for different scenarios.
- Experiment with the code to explore how growth rates affect population dynamics.

## Acknowledgments

Based on *Modeling and Simulation in Python* by Allen Downey. Visit [the book's website](https://greenteapress.com/wp/modsimpy/) for more resources.