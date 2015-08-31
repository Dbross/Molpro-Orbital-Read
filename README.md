# Molpro-Orbital-Read
This is a python script that reads a molpro output and looks for certain keywords involved with printed orbitals. This works for both the M
CSCF and SCF modules, and could work for others, but these have not been debugged. If invoked with no arguments it will ask for the input
file name and a threshold below which to not print the coefficients. If arguments are supplied, it will assume that they are:
$ Filepath (valid file in path) $ threshold (valid float)

The script then outputs to the standard out. The main purpose of this program is quickly checking ab initio outputs to assign character to
orbitals. 
The numbering of the atoms is the same as the molpro ordering. The numbering of each orbitals (e.g. 1s, 2s, etc) is by the number in molpro, e.g. the first s orbital on atom 1 is 1 1s, the second 1 2s.

