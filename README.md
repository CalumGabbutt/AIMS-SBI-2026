[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/CalumGabbutt/AIMS-SBI-2026/blob/main/AIMS_SBI_2026.ipynb
)

# Simulation based inference (SBI) project for AIMS 2026

This notebook gives a practical example of simulation based inference (SBI), applied to the biological system of stem cell dynamics. The model is a stochastic version of how stem cell dynamics pattern methylation data, described here: [Fluctuating methylation clocks for cell lineage tracing at high temporal resolution in human tissues](https://doi.org/10.1038/s41587-021-01109-w)

By the end of this notebook, you should be able to:

*   Explain simulation-based inference and why it is needed
*   Understand the stochastic biological simulation and what effect the parameters have on the simulated data
*   Implement Neural Posterior Estimation (NPE) for a stochastic model
*   Justify choices of summary statistics / embeddings
*   Diagnose posterior quality using posterior predictive checks (PPC) and simulation-based calibration (SBC) checks
*   Critically assess failure modes of SBI
