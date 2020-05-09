Input files for the Steered MD

Several attemps with different force constantes were tried in this study, however here we only upload the one whihc was later used for creating the set of pdb structures defining the activation/inactivation pathway

**SYSTEM INFO**

Protein sequence from https://www.uniprot.org/uniprot/P07550

Aminoacid sequence modelled: 29:238 - 260:342

No ligand was present in the receptor

Sodium was not present in the DRY cavity.
D2.50 protonated

POPC membrane, 0.15M NaCl, TIP3 waters

FF: Charmm36

Input ready to run with GROMACS (2018.X 2019.X) and PLUMED 2.5.X or higher

**SIMULATIONS DETAILS**

Here we start from and Active-like conformation and we end as close as possible to an inactive-like conformation.

The Steering is carried out by minimizing the RMSD value betwwen the main TM differences between both states (TM1 res29:60 , TM6 res267:285, TM7 313:339). Reference PDBs were extracted from the crystal structure from 3SN6 and 2RH1

The pulling force was constant along the steering. The Kappa parameter, used to calculate the pulling force was set to 50000 units in this simulation. Different test were done with lower values of Kappa, however the final RMSD was not as low as the achieved with this value.
