# BrepPhyloAnalysis
Analysis done for the BrepPhylo paper on COVID, Ebola and RSV repertoires

Joseph Ng ([@josef0731](https://github.com/josef0731)), June 2021

This repository contain R markdown notebooks for analysis performed for this work. Both the R markdown files and the HTML notebooks are available.

## Content

### Markdown & Notebooks

* `ClonalDiversity`: Analysis of clonal diversity (clone size, gini diversity etc) 
* `convergence-ebola`: Analysis for 'convergent' sequences from the repertoire shared across Ebola patients, and converging towards known binders of Ebola virus proteins from the literature.
* `convergence-covid`: Analysis for 'convergent' sequences from the repertoire shared across COVID-19 patients, and converging towards known binders of SARS-CoV-2 proteins from the literature.
* `convergence-RSV`: Analysis for 'convergent' sequences from the repertoire shared across volunteers (infected/uninfected) in the RSV live challenge trial, and converging towards known binders of RSV proteins from the literature.
* `CSR`: Analysis of frequency and distance-from-germline of Class-Switch Recombination events detected from lineage trees.
* `GeneUsage`: Analysis of V, D, J gene usage. Separation by age groups.
* `MutationalLevels`: Analysis of mutational levels in lineage trees.

### Folders

* `known_binders`: Curation of known antibodies targetting specific antigens from the Protein Data Bank (PDB) & from the literature.
