To use either dilate or ghost, you need the xyz coordinates, e.g. ethene-dimer.txt, and a rem vector in file "rem".
The xyz coordinates are expected to be separated by a single space.  This could be improved.  Additionally, the scripts do not expect a header with number of atoms for .txt files.

You can run these scripts as follows
dilate ethene 6 6 0.5 1.5 0.1
ghost ethene 6 6 0.5 1.5 0.1
