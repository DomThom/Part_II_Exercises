# General Huckel Solver

## Inputs

Running the code will open an input box to allow the user to select from a 
list of possible inputs by inputting a number.
N.B. IPUAC name input requires an internet connection to allow it to be
converted to a SMILE string.

Inputs can be in the form:
  1. IUPAC molecule name
  2. n where n is the number of vertices in a given Platonic solid
  3. SMILE string of a molecule
 
Program will assume all atoms in the molecule are involved in the pi system
meaning that any molecule with the same adjacency will give the same result.

## Required libraries
numpy
pysmiles
networkx
urllib
scipy

## Complete tasks?

Linear and cyclic polyenes, buckminsterfullerene: IUPAC or SMILE inputs work
(for the polyenes can input the polyene name or just the alkane with the same
shape as stated before only adjacency is considered!)

Platonoic solids: use the platonic solids dictionary
