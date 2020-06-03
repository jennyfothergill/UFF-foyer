### UFF

#### This forcefield is still a work in progress -- use at your own risk!
* Angles and dihedrals are not yet implemented!

This repository provides [foyer](https://github.com/mosdef-hub/foyer) and [GMSO](https://github.com/mosdef-hub/gmso) compatible XML files for the Universal Forcefield (UFF).

 * Source: Rappé, A. K., Casewit, C. J., Colwell, K. S., Goddard, W. A., & Skiff, W. M. (1992). UFF, a Full Periodic Table Force Field for Molecular Mechanics and Molecular Dynamics Simulations. Journal of the American Chemical Society, 114(25), 10024–10035. [https://doi.org/10.1021/ja00051a040](https://doi.org/10.1021/ja00051a040)

 * Forcefield file initially created March 31, 2020 by Jenny Fothergill

#### Additional Notes:
 
 * UFF units are given in the Rappé paper as angström, deg, kcal/mol, but foyer uses nm, rad, kJ/mol
 * 4.184 is used as the conversion between kcal and kJ (1 kcal = 4.184 kJ)
 * The harmonic bond force is defined as <img src="https://render.githubusercontent.com/render/math?math=E_{R} = \frac{1}{2}k_{ij}(r-r_{ij})^{2}"> where <img src="https://render.githubusercontent.com/render/math?math=r_{ij} = r_{i} %2B r_{j} %2B r_{BO} %2B r_{EN}"> where <img src="https://render.githubusercontent.com/render/math?math=r_{i}"> and <img src="https://render.githubusercontent.com/render/math?math=r_{j}"> are provided and <img src="https://render.githubusercontent.com/render/math?math=r_{BO}"> and <img src="https://render.githubusercontent.com/render/math?math=r_{EN}"> are calculated based on the bond order and the electronegativity. In this implementation, we have simplified these terms to be 0.026 Å which fits the C-C single bond to 1.54 Å.
 
### Force field DOI
(not complete)
<TODO>[![DOI](https://zenodo.org/badge/XXX/USER_NAME/YOUR_FORCEFIELD_REPO.svg)](https://zenodo.org/badge/latestdoi/XXX/USER_NAME/YOUR_FORCEFIELD_REPO)</TODO>

