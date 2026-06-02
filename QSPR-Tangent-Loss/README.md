# Yu 2008 Tan-Loss QSPR Reproduction

This repository contains a Jupyter notebook and input data for reproducing a tan-loss QSPR workflow based on Yu et al. 2008, using AMS/PLAMS and DFTB descriptors.

## Contents

- `yu2008_tanloss_dftb_reproduction_clean.ipynb`: public notebook with outputs cleared.
- `yu2008_dftb_reproduction_data/yu2008_materials.csv`: material and structure proxy definitions.
- `yu2008_dftb_reproduction_data/yu2008_tanloss_observations.csv`: tan-loss observations used by the notebook.

## Software Used

The notebook uses:

- Python
- AMS/PLAMS
- NumPy
- pandas
- scikit-learn
- matplotlib
- RDKit

The DFTB descriptor section requires a working AMS installation with PLAMS available in the Python environment.

## How to Run

1. Open `yu2008_tanloss_dftb_reproduction_clean.ipynb` in Jupyter.
2. Make sure the folder `yu2008_dftb_reproduction_data` is in the same folder as the notebook.
3. Run the notebook cells from top to bottom.

The notebook writes generated results to `yu2008_dftb_reproduction_outputs/`. That output folder is not included here.

## Reference

X. Yu, B. Yi, F. Liu, X. Wang, "Prediction of the dielectric dissipation factor tan delta of polymers with an ANN model based on the DFT calculation", Reactive & Functional Polymers 68, 1557-1562, 2008. DOI: `10.1016/j.reactfunctpolym.2008.08.009`.
