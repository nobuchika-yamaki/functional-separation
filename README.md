Reproducible Analysis Code for Delayed Asymmetric Systems

This repository contains a single, self-contained Python script that reproduces all numerical results and figures reported in the manuscript
“Functional separation of sensitivity and coordination in asymmetric delayed systems.”

Contents

Main nonlinear delayed two-unit model

Sensitivity analysis via Fisher information

Coordination analysis via information–phase index

Comparison with delayed Kuramoto phase model

Robustness across nonlinearity strength (κ)

Validation with delayed Stuart–Landau oscillators (shear and noise effects)

How to run
python run_all_analyses_review_ready.py


No input data files are required. All simulations are generated internally.

Outputs

All results are written to the outputs/ directory:

CSV files: numerical values used in the Results section

Figures (PNG):

Figure 1: Symmetric-delay dynamics and mode decomposition

Figure 2: Separation between sensitivity and coordination

Figure 3: Kuramoto comparison and κ-robustness

Figure 4: Stuart–Landau mechanism (shear and noise)

Legends are placed outside plots to avoid overlap, and figures are formatted for direct inclusion in Word or LaTeX manuscripts.

Notes

Delay asymmetry is controlled in absolute time (seconds).

Normalized delay ratios use empirically estimated timescales; if unavailable, model-based periods are used.

Fisher information is computed under a Gaussian approximation for numerical stability and interpretability.

This code is intended for full reproducibility and peer review.
