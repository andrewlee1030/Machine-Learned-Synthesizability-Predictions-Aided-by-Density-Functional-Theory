# Introduction

This repository includes code and data used in the following study: [Machine Learned Synthesizability Predictions Aided by Density Functional Theory](https://www.nature.com/articles/s43246-022-00295-7).


# Files/Directories and their descriptions



**gen_list_icsd.ipynb**: processes cif files downloaded from the Inorganic Crystal Structure Database (ICSD) and identifies ABC stoichiometry compounds and their space group and prototype names  

**gen_list_springer.ipynb**: processes cif files downloaded from Springer Materials and identifies ABC stoichiometry compounds and their space group and prototype names  

**gen_list_ASM.ipynb**:  processes phase diagram data files downloaded from ASM's Phase Diagram Database and identifies ABC compositions that are expected to phase separate

**icsd_springer_combined_analysis.ipynb**: processes the csv files from gen_list_icsd.ipynb and gen_list_springer.ipynb by checking for conflicting information and identifying agreements and conflicts

**predict_synthesizability.ipynb**: script to run the ML model that predicts synthesizability

**released_Data Files**: directory including output data from each "gen\_" script. Also includes the processed training data required to run the ML model. Raw data used in "gen\_" scripts are not included for copyright reasons (.cif files and data require paid licenses)
