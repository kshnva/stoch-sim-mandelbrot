# Mandelbrot Set Area Estimation

Assignment 1 for the Stochastic Simulations course at the University of Amsterdam. This project estimates the area of the Mandelbrot set using Monte Carlo sampling techniques, comparing pure random sampling, Latin hypercube sampling, and orthogonal sampling. The analysis examines convergence rates, confidence intervals, and variance reduction across methods.

## Key Tools and Libraries

- **Python 3.12** with **Jupyter Notebook**
- **NumPy** and **SciPy** for numerical computation and statistical analysis
- **Matplotlib** for visualisation
- **uv** for dependency management
- **pre-commit** with **ruff** (linting/formatting) and **nbstripout** (notebook cleanup)

## Repository Structure

- `final_assignment1.ipynb` — Final consolidated notebook
- `notebook/` — Working notebooks (development drafts)
- `StochSimKush.ipynb` — Individual exploration notebook
- `pyproject.toml` — Project metadata and dependencies
- `Assignment 1 - MANDELBROT.pdf` — Assignment specification

## How to Run

1. Install [uv](https://docs.astral.sh/uv/):
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
2. Install dependencies:
   ```bash
   uv sync
   ```
3. Launch Jupyter:
   ```bash
   uv run jupyter lab
   ```
4. (Optional) Set up pre-commit hooks:
   ```bash
   uv tool install pre-commit --with pre-commit-uv --force-reinstall
   pre-commit install
   ```

## Course

Stochastic Simulations, MSc, University of Amsterdam
