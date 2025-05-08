# 🧬 Dynein-Tubulin Interactions via Molecular Dynamics Simulation

## Overview
This project uses *all-atom molecular dynamics (MD) simulations* to explore the intricate interactions between the Microtubule Binding Domain (MTBD) of cytoplasmic dynein and the α, β-tubulin heterodimer in neuronal cells. The study models conformational shifts, binding interactions, and electrostatic relationships at the dynein-tubulin interface, with a focus on how these dynamics relate to intracellular transport and neurodegenerative disease mechanisms.

## Key Features
- Simulated dynein-tubulin interactions over a 320 ns trajectory using **GROMACS** with the **GROMOS 54A7 force field**
- Analyzed structural changes using RMSD, RMSF, dCOM (distance between centers of mass), and salt bridge interactions
- Focused on C-terminal tubulin tails (CTTs), which play a critical role in dynein’s binding affinity and motility
- Provided structural and mechanistic insights into how dynein malfunction may relate to diseases like Alzheimer’s, Huntington’s, and ALS

## Technologies & Tools
- 🧪 GROMACS for molecular dynamics simulations  
- 🐍 Python with MDAnalysis for data extraction and plotting  
- 🧬 PyMOL and VMD for molecular visualization  
- 🖥️ High-Performance Computing on Graham (Digital Research Alliance of Canada)

## Outcomes
- Identified critical residues and helices (e.g., MTBD-H1, H3, H7) involved in binding dynamics
- Observed dynamic behavior in electrostatic salt bridges that modulate dynein affinity
- Contributed to the understanding of molecular transport mechanisms in neurons and their implications in neurological disorders

## Repository Structure
```
dynein-tubulin-md/
│
├── data/                # Raw structure files, trajectory files
├── analysis/            # Python scripts for RMSD, RMSF, dCOM, salt bridges
├── figures/             # Visualizations (PyMOL, VMD, plots)
├── results/             # Output data from MDAnalysis
├── README.md            # Project overview and instructions
```

## Citation
If you use this repository, please cite:
> Dave, N. (2023). Exploring Cytoplasmic Dynein and α, β-Tubulin Heterodimer Interactions: Insights from Molecular Dynamics Simulations on Neuronal Function and Disease. Honours Thesis, Memorial University of Newfoundland.
