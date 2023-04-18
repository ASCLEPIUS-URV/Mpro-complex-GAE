# Mpro-complex Graph Data

Each instance in the set is a graph describing the whole ligand and part of the protein where its atoms and bonds are believed to be involved the interaction site. Specifically, prtoeins atoms were selected to be at a distance lower than seven Angstrom. Graph nodes are atoms of both, the ligand and the protein. Attributes on the nodes are the three-dimensional positions of the atoms that represent and their atomic number. Edges are unattributed and the generated graphs have 146 nodes.

- The file "URV-Complex-Mpro.mat" contains 107 M-pro crystallized structures bound to an inhibitor for which its pIC50 is known, and 53 ligand complexes calculated from ligands obtained through FRAGALYSIS https://fragalysis.diamond.ac.uk/viewer/react/preview/target/Mpro, and The Protein Databank (PDB) https://www.rcsb.org/.

# Mpro ligand potency data

The file"URV-Activity-Mpro.mat" contain the ligand pIC50 values.



# GAE and Autoencoder
The Graph Autoencoder and autoencoder can be run from the entry-point file, "Run_Mpro.mat". Hyperparameters are in the Configuration_MPro.m
