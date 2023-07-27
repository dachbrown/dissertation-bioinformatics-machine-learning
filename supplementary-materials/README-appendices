APPENDIX A: HARDWARE SPECIFICATIONS

Code development and testing took place on a desktop iMac (27-inch, Late 2012) provided by the UNC
Charlotte Department of Bioinformatics and Genomics.
  – Processor: 2.9 GHz Quad-Core Intel Core i5
  – Memory: 16 GB 1600 MHz DDR3  

Research computing resources provided by the UNC Charlotte Research Computing
group. I used the HPC cluster, which runs Red Hat Enterprise Linux and is managed
by SLURM (https://oneit.charlotte.edu/urc/our-environment) [Internet]. Resource
requests were for one or multiple of the following nodes:
  - Dual 18-Core Intel Xeon Gold 6154 CPU @ 3.00GHz (36 cores / node)
  - 388GB RAM (10.7GB / core)
  - 100Gbit EDR Infiniband Interconnect

-----
-----

APPENDIX B: ANACONDA ENVIRONMENTS

Fourteen files (suffix “.yml”) for creating the various Anaconda environments used
in this research. Both the full list of dependencies for the UNC Charlotte UPC
architecture and the historical requests (parameter --from-history) to create them
are included.  

For snp-sites
  – 290B hpc_binf_snp-sites_environment_from_history.yml
  – 5.7K hpc_binf_snp-sites_environment_full.yml  

For CheckM
  – 213B hpc_checkm_environment_from_history.yml
  – 4.4K hpc_checkm_environment_full.yml  

Base Python 3 bioinformatics environment for data exploration and manipulation
  – 1.3K hpc_galick_gun_environment_from_history.yml
  – 2.6K hpc_galick_gun_environment_full.yml  

For Gotree
  – 160B hpc_gotree_environment_from_history.yml
  – 841B hpc_gotree_environment_full.yml  

For machine learning on imbalanced data with scikit-learn
  – 229B hpc_ml_imba_environment_from_history.yml
  – 5.2K hpc_ml_imba_environment_full.yml  

For Prokka and Roary
  – 18K hpc_prokka_environment_from_history.yml
  – 11K hpc_prokka_environment_full.yml  

For R
  – 300B hpc_r_for_vs_code_env_environment_from_history.yml
  – 8.6K hpc_r_for_vs_code_env_environment_full.yml

-----
-----

APPENDIX C: EXAMPLE RAxML SUBMISSION TO SLURM

Contains a single file (suffix “.slurm”) of a RAxML submission script to SLURM on
the UNC Charlotte HPC architecture. Includes settings for SLURM resource requests
and RAxML parameters.
  - 5.1K hpc_raxml_settings.slurm

-----
-----

APPENDIX D: SUPPLEMENTARY DATA

Contains four files from this investigation: a phylogenetic tree (suffix “.tree”) based
on the core genome of 817 E. coli isolates as determined by Roary (without splitting
paralogs) in Chapter 2, a spreadsheet (suffix “.csv”) of gene annotations created by
Roary (with split paralogs) in Chapter 3, a spreadsheet (suffix “.tsv”) of outputs
from the fitPagel function in phytools, and a spreadsheet (suffix “.tsv”) of combined
annotations from Roary and BLAST.  

Phylogenetic tree from Chapter 2
  – 27K RAxML_rootedTree.900_ns_core_opt.ROOTED.tree  

Roary annotations from Chapter 3
 – 242M gene_presence_absence.csv  

fitPagel outputs from Chapter 2
  – 29K hpc_output_pagel_full_adjusted.tsv  

Annotations from Roary and BLAST
  – 690K joined_blast_roary_annotations.tsv
