# Distributionally-robust detection of external forcings under climate interventions

Robust-detection is a Python package for testing detection of climate change.

## Installation

Install the virtual environment with conda and activate it:

```bash
conda env create -f environment.yml
conda activate robustDA
```

Install robustDA in the virtual environment:

```bash
pip install -e .
```

Run using python3 with the parameters specified in the params.yml file

```bash
python3 main.py --help
python3 main.py --exp HT 
```

Run the jupyter notebook:

```bash
jupyter notebook
```

To deactivate the environment use:
```bash
conda deactivate
```


## Structure

## References

## Data

The CMIP6 (Coupled Model Intercomparison Project, Phase 6) data is available at [https://esgf-node.llnl.gov/projects/cmip6/](https://esgf-node.llnl.gov/projects/cmip6/).
