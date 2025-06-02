# triclinic_unwrapping

This is a repo to test different methods for unwrapping trajectories in periodic triclinic cells.

## unwrapping.ipynb
unwrapping.ipynb contains two unwrapping schemes. The first scheme involves taking all 9 periodic images, in 2d space. The second scheme uses the method of a madman which involves wrapping the displacement vectors into a sectioned space, and wrapping based on the section the vector falls into (I will make this more elequent in time). The code is written to test on a known set of coordinates, and should return the same answer for both schemes. Effort was made to write this code in as simple a way as possible and therefore it is sub-optimal.

## bisector.ipynb
bisector.ipynb contains a description of the madmans scheme, and how it can be constructed from just the lattice parameters: a, b, and alpha.
