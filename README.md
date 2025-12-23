# Building AI course – small AI project

## Summary
This repository contains a small AI project created as part of the **Building AI** course.  
The aim is to practise core machine learning workflows in Python: from loading and cleaning data to training simple models and evaluating their performance.

## Contents
- Example workflows for:
  - Data loading, cleaning and basic preprocessing
  - Simple models (e.g. linear regression, k‑nearest neighbours, logistic regression)
  - Model evaluation with straightforward metrics (accuracy, MSE, etc.)
- Jupyter notebooks illustrating individual concepts step by step
- Reusable Python utility functions for data handling and model training

## Project structure
```
.
├─ data/               # Example datasets (toy data for practising)
├─ notebooks/          # Jupyter notebooks used in the course
├─ src/                # Python source files (models, utilities)
├─ requirements.txt    # Python dependencies
└─ README.md
```

## Requirements
- Python 3.x
- Recommended libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `jupyter`

Install dependencies:

```
pip install -r requirements.txt
```

## How to run

Run an example script:

```
python src/example_model.py
```

or start the notebooks:

```
jupyter notebook notebooks/
```

## Development notes
- Code style: follow basic PEP 8 conventions for Python.
- Experiments: feel free to add new notebooks to `notebooks/` to try out ideas from the Building AI course.

## License
This project is intended for educational purposes as part of the **Building AI** course.  


