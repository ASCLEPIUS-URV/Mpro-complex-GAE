# Mpro-complex Graph Data

Each instance in the set is a graph describing the whole ligand and part of the protein where its atoms and bonds are believed to be part of the interaction site. Specifically, prtoein atoms were selected to be at a distance lower than seven Angstrom. Attributes on the nodes are the three-dimensional positions of the atoms and their atomic number. Edges are unattributed and the generated graphs have 146 nodes.

- The file "URV-Mpro-Complex.mat" contains 107 M-pro crystallized structures bound to an inhibitor for which its pIC50 is known. The ligands were obtained through FRAGALYSIS https://fragalysis.diamond.ac.uk/viewer/react/preview/target/Mpro. The remaining 53 complex graphs were calculated using ligands from The Protein Databank (PDB) https://www.rcsb.org/.

# Mpro ligand potency data

The file"URV-Mpro-Activity.mat" contains the ligand pIC50 values.



# GAE and Autoencoder
The Graph Autoencoder and autoencoder can be run from the entry-point file, "Run_Mpro.mat". Hyperparameters are in the Configuration_MPro.m
Regression can be calculated using semantic features, strucutral features, or a combination of both. To modify this, comment/uncomment the corresponding variable "r" in the file "Z_Compress.m"

