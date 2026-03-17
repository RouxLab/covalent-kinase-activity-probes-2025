# Kinetic Modeling of Covalent Kinase Probes

The Jupyter notebook in this repository can be used to reproduce the kinetic modeling and analysis of the covalent kinase probes as discussed in [ref. 1](https://doi.org/10.1021/jacs.5c18691).

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
conda activate covalent_probe_analysis
```

## Contact
Feel free to open an issue or email kyleghaby@gmail.com with questions about using the workflow.

## References

1. Chakraborty, P.\*; Carlos, A.\*; Thomas, T.\*; Ghaby, K.; Fathi, S.; Sharma, M.; Nguyen, N. K.; Farmwald, M.; Blachowicz, L.; Alcyone, E.; Harter, K.; Yu, S.; Pillai, K. S.; Roux, B.; Moellering, R. E. Molecular Dynamics-Guided Design and Chemoproteomic Profiling of Covalent Kinase Activity Probes. *J. Am. Chem. Soc.* **2026**. DOI: [10.1021/jacs.5c18691](https://doi.org/10.1021/jacs.5c18691)

\* These authors contributed equally.

