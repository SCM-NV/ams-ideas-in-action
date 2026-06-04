# Full NIST Binary Surface Tension Prediction

This folder contains a standalone AMS Python notebook for fitting binary liquid surface tension on the full neutral-binary subset of the NIST data package at DOI `10.18434/mds2-2962`.

The example uses curated NIST surface-tension data, RDKit descriptors, SG1 FastSigma sigma moments, and PropPred pure-compound properties. Saved output files are included for reference.

## Contents

- `binary_surface_tension_standalone_full_nist_example.ipynb`: notebook as received.
- `binary_surface_tension_standalone_full_nist_example_executed.ipynb`: executed notebook as received.
- `data/raw/`: original NIST source files used for provenance and inspection.
- `data/processed/`: curated tables used by the regression workflow.
- `outputs/`: saved result table, prediction table, parity plot, and summary file.

## Requirements

Run the notebook in the AMS Python environment.

SG1 may need to be installed first:

```bash
"$AMSBIN"/amspackages install molsg_sg1db
```

The notebooks expect the `data/raw` and `data/processed` folders to be present next to them.

## How to Run

1. Open the notebook in AMS Python or another Jupyter environment configured with AMS.
2. Confirm that `data/raw` and `data/processed` are in the same folder as the notebook.
3. Run the notebook cells from top to bottom.
4. The optional save cell writes tables, a parity plot, and a summary to `outputs/`.

## Reference Data

NIST data package: `10.18434/mds2-2962`.
