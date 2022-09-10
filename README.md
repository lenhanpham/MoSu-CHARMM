# MoSu-CHARMM

MoSu-CHARMM force field developed and reported in the paper "Predicting Biomolecule Adsorption on MoS₂ Nanosheets with High Structural Fidelity" https://doi.org/10.1039/D1SC06814H can obtaied here. The force field is ready for use. I'll spend a bit more time to write instruction on how to use MoSu-CHARMM. Basically, MoSu-CHARMM  was developed to be used with GROMACS, and therefore can be used with the command gmx pdb2gmx. 

Since several new atomtypes have been newly introduced in MoSu-CHARMM, the gmx pdb2gmx might not cover all bond types, angle types, and dihedral types. You might want to manually add these bonded paramters to MoSu-CHARMM to make it work for your proteins and peptide chains. You can give me a message, and then I can add all new bonded parameters for your case.

MoSu-CHARMM can work with all types of organic compounts as well.

# Usage of MoSu-CHARMM Force Field 

**MoSu-CHARMM** is a high-fidelity force field for simulation interaction
between biomolecules (peptides and proteins) & all possible organic compounds
and the MoS<sub>2</sub> surface in aqueous media. MoSu-CHARMM can be used for
gas-phase simulation as well. In order to use MoSu-CHARMM in aqueous media, the
TIPS3P water model should be used. Parameters for description of interaction
between water and MoS<sub>2</sub> can be found in another publication "**Pham,
L. N.; Walsh, T. R.** *Force Fields for Water–Surface Interaction: Is
Reproduction of the Experimental Water Contact Angle Enough?* **Chem. Commun.**
***2021***, 57 (27), 3355–3358.
[doi:10.1039/d1cc00426c](https://doi.org/10.1039/D1CC00426C)". All parameters in
the Chem. Sci. paper, together with parameters in the Chem. Comm. one, make
MoSu-CHARMM complete.  

## **Users need to pay attention to setting parameters such as vdw cutoff and rcoulomb when using MoSu-CHARRM. These parameters are mentioned in two papers above.*

# Please cite these two publications if you use MoSu-CHARMM in your works

**1.**  "**Pham, L. N.; Walsh, T. R.** *Force Fields for Water–Surface Interaction: Is
Reproduction of the Experimental Water Contact Angle Enough?* **Chem. Commun.**
***2021***, 57 (27), 3355–3358.
[doi:10.1039/d1cc00426c](https://doi.org/10.1039/D1CC00426C)".

**2.** **Pham, L. N.; Walsh, T.** *Predicting Biomolecule Adsorption
on MoS<sub>2</sub> Nanosheets with High Structural Fidelity.* **Chem. Sci.** ***2022***
[doi:10.1039/D1SC06814H](https://doi.org/10.1039/D1SC06814H)
