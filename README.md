# db_codebase => Discordant Bioinformactic codebase README

This is the code accompanying the paper 
"Discordance between different bioinformatic methods for identifying resistance genes from short-read genomic data, with a focus on Escherichia coli"
https://doi.org/10.1101/2021.11.03.467004
Available at https://www.biorxiv.org/content/10.1101/2021.11.03.467004v1

## Included 
For different sections of the paper there is a different folder (Main analysis, flex and dual simulations, coverage simulations not included as these generated simply by changes to art_illumina running code)
For each one there is a jupyter notebook which is the running code. Note I have included all of the result tarballs, although these need to be unpacked prior to use.
To run each, extract the result tarballs, and then run the main notebook
Note each notebook also references back to the db used (which was formatted in a standard way so all programs can use it without risk of formatting problems)
So will need the db_preparation folder
Note as designed the file structure should give appropriate paths for things, i.e. if you download this entire repository and extract the code should be runnable

### Sequencing file locations
- PRJNA779173 , https://www.ncbi.nlm.nih.gov/bioproject/PRJNA779173 , Samples uploaded for the purpose of this study (PHE, resistance mechanisms of note)
- PRJNA604975 , https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA604975, 8 additional oxfordshire samples uploaded 
- PRJNA540750 , https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA540750, Samples uploaded for https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7269502/ (Oxfordshire)
- PRJEB26317 ,  https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJEB26317, Samples uploaded for https://pubmed.ncbi.nlm.nih.gov/34122397/
(APHA samples)

Please see additional spreadsheed for each item location

### original files from simulations available on request
