# BiChI

Repository for paper: Relativistic Electronic Structure and Band Alignment of BiSI and BiSeI: Candidate Photovoltaic Materials

DOI:[10.1039/C5TA09612J](http://pubs.rsc.org/en/content/articlelanding/2016/ta/c5ta09612j)

Optimised crystal structures of BiSI and BiSeI from density functional theory, calculated using the Vienna *Ab initio* Package (VASP).

Computational Details
-----------------------
The crystal structures of BiSI and BiSeI obtained by Haase-Wessel<sup>1</sup> and Braun et al.<sup>2</sup> were used as the starting point for the calculations.

We have optimised the structures using 4 different functionals: PBEsol, PBEsol + Grimme’s D3 dispersion correction (PBEsol+D3), PBE, and PBE+D3.
The final structures have been obtained following an iterative procedure where the ion positions, cell shape, and cell volume are allowed to change (`ISIF = 3` in VASP) using a Quasi-Newton algorithm.

Requirements
------
To open the .cif file, a viewer such as [VESTA](http://jp-minerals.org/vesta/en/).
To run the `POSCAR` file: a VASP license, and suitable input `INCAR`, `KPOINTS`, and `POTCAR` files.

Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.

References
-------
1. W. Haase-Wessel, Die Kristallstruktur des Wismutsulfidjodids (BiSI), *Naturwissenschaften*, **60**, 474-474 (1973) doi: [10.1007/BF00592859](http://link.springer.com/article/10.1007%2FBF00592859) 
2. T. P. Braun and F. J. DiSalvo, Bismuth selenide iodide, *Acta Cryst.*, **56**, 1-2 (2000) doi: [10.1107/S0108270199016017](http://scripts.iucr.org/cgi-bin/paper?S0108270199016017)
