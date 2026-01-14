# Dual-LAO Simulation Inputs

This repository contains all necessary input files to execute **dual-LAO simulations** for each specified target and ligand pair. The data is organized by target protein, then by specific ligand pairs, covering both the complex and solvent phases.

## Directory Structure
The internal folder hierarchy is organized as follows:

```plaintext
Target/
└── [Pair_Name]/
    ├── complex/          # Parameters and coordinates for the protein-ligand system
    │   ├── input.xyz     # Tinker XYZ Cartesian coordinates
    │   ├── input.key     # Tinker keyword file (force field parameters)
    │   ├── colvars.in    # Collective Variables (Colvars) input
    │   └── ref.xyz       # Reference structure for RMSD/alignment
    └── solvent/          # Parameters and coordinates for the ligand in water
        ├── input.xyz
        ├── input.key
        ├── colvars.in
