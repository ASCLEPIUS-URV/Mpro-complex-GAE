# Mpro-complex
The set contains 107 M-pro crystallized structures bound to an 180 inhibitor for which its pIC50 is known. They come from the FRAGALYSIS https://fragalysis.diamond.ac.uk/viewer/react/preview/target/Mpro. Each instance consists of graph describing the whole ligand and only the atoms and bonds of the protein that are close to some atom of the ligand. Specifically, at a distance lower than seven Angstrom. Graph nodes are atoms of both, the ligand and the protein. . Attributes on the nodes are the three-dimensional positions of the atoms that represent and their atomic number. Edges are unattributed and the generated graphs have 123 nodes. The file 'Activity' contains the ligand pIC50 values.

#GAE, AE
The Graph Autoencoder and autoencoder can be run from the entry-point file, Run_Mpro. The data and model hyperparameters can be edited on Configuration_MPro.m.
