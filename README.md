# datafun-07-ml

Professional Python project: Predictive Machine Learning with Jupyter notebooks.
Author: Jennifer Danielson

---

## Project Overview

This project begins Module 7 and focuses on building a predictive machine learning workflow using Python and Jupyter notebooks. The goal is to establish a clean, professional, repeatable project structure and development process.

This project uses:

- Python
- JupyterLab
- NumPy
- Pandas
- PyArrow
- Matplotlib
- Seaborn
- SciPy

---

## Project Setup

Clone the repository and create a local virtual environment:

```shell
cd C:\Repos
git clone https://github.com/jmdanielson82/datafun-07-ml.git
cd datafun-07-ml

python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy
```

## Daily Workflow

Start each work session:
```shell
git pull
.\.venv\Scripts\Activate.ps1
jupyter lab
```

Save progress frequently:
```shell
git add -A
git commit -m "Describe update"
git push
```

## Repository Structure

- `notebooks/` — Primary analysis notebooks
- `src/` — Python source files (if used)
- `data/` — Project datasets
- `docs/` — Documentation files
- `pyproject.toml` — Project metadata and dependencies
- `README.md` — Project overview and workflow documentation  

## Status
Initial project setup complete. Ready to begin predictive modeling exploration.
