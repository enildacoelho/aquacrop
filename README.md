# aquacrop-OSPyML

PhD project: aquacrop-OSPyML — reproducible experiments and thesis materials for modeling with AquaCrop, OSPy and machine learning in Python.

Contents
- src/: core package code
- notebooks/: interactive analyses and reproducible examples
- tests/: unit and integration tests
- thesis/: LaTeX thesis source
- data/: sample datasets
- environment.yml: conda environment for Binder/Colab
- .github/workflows/: CI for tests

Quickstart
1. Create the conda environment: `conda env create -f environment.yml`
2. Activate: `conda activate aquacrop-ospyml`
3. Run tests: `pytest -q`
4. Open notebooks in `notebooks/` or launch Binder from the repository

License: CC-BY-4.0 (applies to code and thesis content)

Author: enildacoelho