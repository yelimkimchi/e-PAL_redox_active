# e-PAL_redox_active
Using the e-PAL (e-Pareto Active Learning) algorithm to identify ideal redox active materials for redox flow batteries based on the reduction potential, 
solvation energy, and absorption wavelength of the molecules in the dataset. 
e-PAL_gitub - contains (1) extracting descriptors for each molecule used to predict their potential, solvation energy, and wavelength 
                       (2) preprocessing data 
                       (3) running the e-PAL algorithm based on LGBM REgressor to generate a set of molecules with optimal properties. 
E-PAL_GPR -same as ePAL but using GPR instead of LGBM as the surrogate model
AllProps_1400BzNSN - dataset of the molecules and their DFT-calculated potential, solvation energy, and wavelength, 
                     data source: https://github.com/MolecularMaterials/COBOL/tree/main/case-study/multi-objective-BzNSN
