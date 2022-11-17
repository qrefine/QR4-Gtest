# QR4-Gtest
Gradient error analysis from Optimal clustering for quantum refinement of biomolecular structures: Q|R#4

1. Atomic model and reflection data files have been obtained from the RCSB PDB Database and then refined using phenix.refine using default settings. The model was next completed by adding hydrogen atoms using the qr.finalise tool that is part of the Q|R software suite.

2. Gradient analysis were performed using qr.gtest and qr.granalyse. In qr.gtest gradients were computed using the TeraChem and xtb packages as QM engines, with HF-gCP-D3/6-31G and GFN1-xTB as quantum methods. The commands and all relevant input and output files are provided taking 3ftL, two clusters, single- and double-buffer cases with GFN1-xTB method as examples. See Gtest_granalyze_example_3ftL_GFN1-xTB directory.

3. PDB files with atomic gradient errors written into the B-factor field are collected in directories labelled by relevant sections from the manuscript: 3.1_supersphere, 3.2_clustering, 3.3_buffer_3ftL_and_3q2c, 3.4_larger_proteins.
