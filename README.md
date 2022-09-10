# MoSu-CHARMM

MoSu-CHARMM force field developed and reported in the paper "Predicting Biomolecule Adsorption on MoS₂ Nanosheets with High Structural Fidelity" https://doi.org/10.1039/D1SC06814H can obtaied here. The force field is ready for use. I'll spend a bit more time to write instruction on how to use MoSu-CHARMM. Basically, MoSu-CHARMM  was developed to be used with GROMACS, and therefore can be used with the command gmx pdb2gmx. 

Since several new atomtypes have been newly introduced in MoSu-CHARMM, the gmx pdb2gmx might not cover all bond types, angle types, and dihedral types. You might want to manually add these bonded paramters to MoSu-CHARMM to make it work for your protein and peptide chains. You can give me a message, and then I can all new bonded parameters for your case.
