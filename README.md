# CMfg: Dynamic Service Selection and Scheduling in Cloud Manufacturing

This repository contains the source notebook and computational scenario files for research on the Dynamic Service Selection and Scheduling Problem (DSSSP) in project-based Cloud Manufacturing.

## Repository structure

```text
CMfg/
├── README.md
├── Code/
│   └── Dynamic Model of Service Selection and Scheduling in the Cloud Manufacturing Environment.ipynb
└── Scenarios/
    ├── S1-T1.json
    ├── S2-T2.json
    ├── ...
    └── S17-T4T5-Transportation3-AvailabilityFloating.json
```

## Computational scenarios

The `Scenarios/` directory contains 17 JSON files representing the computational scenarios used in the study. The scenarios vary in task composition and, where applicable, transportation and service-unavailability settings. Please consult each JSON file for its precise input parameters.

## Code

The `Code/` directory contains a Jupyter Notebook with the model implementation. Open the notebook using Jupyter Notebook, JupyterLab, or a compatible environment.

## Reproducibility notes

- Preserve the scenario filenames when running experiments so that outputs can be associated with their inputs.
- Record the Python version and required packages used to execute the notebook.
- The model may require IBM ILOG CPLEX and its Python API. Verify the notebook's imports and solver setup before execution.
- Computational results should only be described as reproducible after the required software, data, and execution steps have been verified.

## Citation and DOI

Archived version (Zenodo): https://doi.org/10.5281/zenodo.21774727

Please cite the archived version corresponding to the code and data actually used. If a newer Zenodo version is published, update this section to cite the appropriate version DOI.

## License

A license has not yet been specified. Add a license file and update this section before indicating reuse permissions.
