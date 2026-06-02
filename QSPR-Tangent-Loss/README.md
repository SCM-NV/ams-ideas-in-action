# Yu 2008 Tan-Loss QSPR Reproduction

This folder contains two versions of the same Jupyter notebook for an AMS Ideas in Action example based on Yu et al. 2008.

Use the executed notebook to inspect the reference results. Use the clean notebook if you want to rerun the workflow from a blank state.

## Contents

- `yu2008_tanloss_dftb_reproduction_executed.ipynb`: notebook with reference outputs included.
- `yu2008_tanloss_dftb_reproduction_clean.ipynb`: same workflow with outputs cleared.
- `yu2008_dftb_reproduction_data/yu2008_materials.csv`: material and structure proxy definitions.
- `yu2008_dftb_reproduction_data/yu2008_tanloss_observations.csv`: tan-loss observations used by both notebooks.

## Software Used

The notebooks use:

- Python
- AMS/PLAMS
- NumPy
- pandas
- scikit-learn
- matplotlib
- RDKit

The DFTB descriptor section requires a working AMS installation with PLAMS available in the Python environment.

## How to Run

1. Open `yu2008_tanloss_dftb_reproduction_clean.ipynb` in Jupyter if you want a fresh run.
2. Make sure `yu2008_dftb_reproduction_data` is in the same folder as the notebook.
3. Run the notebook cells from top to bottom.

The notebooks write generated results to `yu2008_dftb_reproduction_outputs/`. That generated output folder is not required to view the executed notebook.

## Reference

X. Yu, B. Yi, F. Liu, X. Wang, "Prediction of the dielectric dissipation factor tan delta of polymers with an ANN model based on the DFT calculation", Reactive & Functional Polymers 68, 1557-1562, 2008. DOI: `10.1016/j.reactfunctpolym.2008.08.009`.
