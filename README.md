The Shannon_entropy directory contains a Python script for computing the entropy of H-bond reorganisation. 
##matrices of protein-ligand Hbond time series were generated using CPPTRAJ output files
##Matrices were utilised to calculate Shannon entropy at each temperature. A sample *.npz file with matrices at two different temperatures has been provided

##Prerequisite: Python and CPPTRAJ
##Command to run the script: python Shannon_Entro-pnpg.py

The str_persistence directory contains a tcl script for computing the structural persistence of protein and of the selected region of the protein (here the active site pocket region).

##Prerequisite: VMD

##Input file needed: trajectory file (.xtc), structure (.pdb). 

##Command to run the script: vmd -dispdev text -e *.tcl


