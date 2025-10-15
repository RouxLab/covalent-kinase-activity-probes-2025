# Kinetic Modeling of Covalent Kinase Probes

The Jupyter notebook in this repository can be used to reproduce the kinetic modeling and analysis of the covalent kinase probes as discussed in [ref. 1][1].

This workflow may be applied to fit time- or dose-response data of any irreversible ligand.

## Environment

This notebook is best used with Python 3.12. The packages used are listed in `environment.yml` and `requirements.txt`.

### Dependencies

- Kinetic modeling (from the Roux Group)
  - `gekim` ([GeKiM](https://github.com/kghaby/GeKiM))

- Numerical analysis
  - `numpy`
  - `lmfit`
  - `arviz`

- Utilities
  - `matplotlib`
  - `dill` (for the MMC data dictionary)
  - `tqdm`

### Installation

Use the following command in the root of a local clone of this repository to create an environment `covalent_probe_analysis` (or a name of your choice assigned in `environment.yml`) for the notebook:

```shell
conda env create -f environment.yml
```

Then,

```shell
conda deactivate
conda activate covalent_probe_analysis
```

### Contact
Feel free to open an issue or email kyleghaby@gmail.com with questions about using the workflow.

## References

1. Carlos, et al. 2024.

[1]: https://github.com/kghaby/GeKiM
