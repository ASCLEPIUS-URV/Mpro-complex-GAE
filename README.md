# Mpro-complex Graph Data
The file "URV-Mpro-FRAGALYSIS.mat" contains 107 M-pro crystallized structures bound to an 180 inhibitor for which its pIC50 is known. These ligands were obtained through FRAGALYSIS https://fragalysis.diamond.ac.uk/viewer/react/preview/target/Mpro. The file "URV-Mpro-FRAGALYSIS.mat" contains the same data with additional 53 ligand complexes obtained from The Protein Databank (PDB) https://www.rcsb.org/.

Each instance consists of graph describing the whole ligand and only the atoms and bonds of the protein that are close to some atom of the ligand. Specifically, at a distance lower than seven Angstrom. Graph nodes are atoms of both, the ligand and the protein. Attributes on the nodes are the three-dimensional positions of the atoms that represent and their atomic number. Edges are unattributed and the generated graphs have 123 nodes in the basic set and 146 in the extended set.

# Mpro ligand potency data
The files "URV-Activity-Mpro-FRAGALYSIS.mat", and "URV-Activity-Mpro-FRAGALYSIS-PDB.mat" contain the ligand pIC50 values of both sets respectively.



# GAE and Autoencoder
The Graph Autoencoder and autoencoder can be run from the entry-point file, "Run_Mpro.mat". Hyperparameters are in the Configuration_MPro.m
