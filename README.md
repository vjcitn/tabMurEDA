# tabMurEDA

exploratory data analysis support for tabula muris single-cell RNA-seq data

droplet counts were retrieved as rds from https://s3.amazonaws.com/czbiohub-tabula-muris/TM_droplet_mat.rds (a dgcMatrix instance), converted
to dense format in HDF5, then uploaded to HDF Kita lab.

DelayedArray infrastructure is embedded in the SummarizedExperiment
tabMurDelayed defined in this package.
