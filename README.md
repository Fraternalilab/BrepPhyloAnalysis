# BrepPhyloAnalysis
Analysis done for the BrepPhylo paper on COVID, Ebola and RSV repertoires

Joseph Ng ([@josef0731](https://github.com/josef0731)), June 2021

This repository contain R markdown notebooks for analysis performed for this work. Both the R markdown files and the HTML notebooks are available.

## Content

### Markdown & Notebooks

* `ClonalDiversity`: Analysis of clonal diversity (clone size, gini diversity etc) ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/ClonalDiversity.html))
* `convergence-ebola`: Analysis for 'convergent' sequences from the repertoire shared across Ebola patients, and converging towards known binders of Ebola virus proteins from the literature. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/convergence-ebola.html))
* `convergence-covid`: Analysis for 'convergent' sequences from the repertoire shared across COVID-19 patients, and converging towards known binders of SARS-CoV-2 proteins from the literature. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/convergence-covid.html))
* `convergence-RSV`: Analysis for 'convergent' sequences from the repertoire shared across volunteers (infected/uninfected) in the RSV live challenge trial, and converging towards known binders of RSV proteins from the literature. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/convergence-RSV.html))
* `convergence-all`: Analysis for 'convergent' sequences from the repertoire shared across RSV, Ebola and COVID-19 repertoires and healthy controls incoporating known binders of Ebola/SARS-CoV-2/RSV proteins in the literature.([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/convergence-all.html))
* `CSR`: Analysis of frequency and distance-from-germline of Class-Switch Recombination events detected from lineage trees. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/CSR.html))
* `GeneUsage`: Analysis of V, D, J gene usage. Separation by age groups. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/GeneUsage.html))
* `MutationalLevels`: Analysis of mutational levels in lineage trees. ([HTML notebook](http://htmlpreview.github.io/?https://github.com/Fraternalilab/BrepPhyloAnalysis/blob/main/MutationalLevels.html))

### Folders

* `known_binders`: Curation of known antibodies targetting specific antigens from the Protein Data Bank (PDB) & from the literature.

### Others

* `convergent_overlap.bib`: references used in the convergent network analysis in bibtex format.
