# Case Studies in DS assignment-1

This repository contains two Jupyter notebooks and the CSV datasets needed to run them locally.

## Files

- `dataset-1.ipynb` uses `data.csv`
- `dataset-2.ipynb` uses `data2.csv`

Keep each notebook in the same folder as its matching CSV file so the relative file paths work correctly.

## Requirements

To run the notebooks locally, install:

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

The notebooks were created with a Python 3 kernel. They should work in a normal Python 3 environment with the packages above installed.

## Local Setup

1. Clone the repository:

```bash
git clone https://github.com/s4161542/Case-Studies-in-DS-assignment-1.git
cd Case-Studies-in-DS-assignment-1
```

2. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

On Windows, use:

```bash
.venv\Scripts\activate
```

3. Install the required packages:

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

4. Start Jupyter:

```bash
jupyter notebook
```

Then open `dataset-1.ipynb` or `dataset-2.ipynb` from the Jupyter interface and run the cells.
