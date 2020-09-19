# Bondlength-Comparison

A simple python code to compare the difference between covalent bondlength taken from VESTA with the bondlength obtained via RDKIT data. This data would help in deciding whether bondlength should be considered from RDKIT or not.

The output is a csv file with following columns
* First atom symbol
* Second atom symbol
* Covalent radius for first atom
* Covalent radius for second atom
* Bondlength form VESTA data
* Difference with skin
* Difference without skin

Note the bondlength from RDKIT data is summation of RCov1, RCov2 and skin
Skin = 0.45
