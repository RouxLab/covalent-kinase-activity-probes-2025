# Kinetic Modeling of KW Probes and XO44

The Jupyter notebook in this repository can be used to reproduce the kinetic modeling and analysis of KW50P, KW60P, and XO44 as discussed in [ref. 1][1].

This workflow may be applied to any irreversible ligand with time- or dose-response data.

## Environment

This notebook should work with Python 3.10, 3.11, and 3.12. The packages used are listed in `environment.yml` and `requirements.txt`.

### Dependencies

- Kinetic Modeling (from the Roux Group)
  - `gekim` ([GeKiM](https://github.com/kghaby/GeKiM))

- Numerical analysis
  - `numpy`
  - `lmfit`
  - `arviz`

- Utilities
  - `matplotlib`
  - `dill` (for the MMC data dictionary, which was serialized in Python 3.11)
  - `tqdm`

### Installation

Use the following command in the root of a local clone of this repository to create an environment `kw_probes` for the notebook:

```shell
conda env create -f environment.yml
```

Then,

```shell
conda deactivate
conda activate kw_probes
```

## References

1. Carlos, et al. 2024.

[1]: https://github.com/kghaby/GeKiM
