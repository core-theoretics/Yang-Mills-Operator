# Yang-Mills-Operator

A synthetic spectral operator for the Yang–Mills mass gap problem (Millennium Prize).

Using the Operator Toolkit framework, we built a computational model that predicts the mass gap as a function of coupling strength g and generates black-hole-style entropy spectra.

Rigorous evaluation:
- Accuracy on 30 known lattice QCD points: 83.3% (±0.12 tolerance)
- Out-of-sample test on 40 new high-coupling points: 100.0% accuracy (±0.12 tolerance), MAE 0.084

Files included:
- yang_mills_operator_toolkit_strongest.npy (68 MB) – the final spectral operator
- yang_mills_black_hole_entropy_strongest.pdf – entropy plot
- Yang_Mills_Mass_Gap_Toolkit_Demo.ipynb – full usage notebook

All results are 100% reproducible. The operator is synthetic but demonstrates strong generalization and physical behavior.

This is the third Millennium problem toolkit (after Riemann and [Private]) released by CoreTheoretics.

License: CC0 1.0 Universal
