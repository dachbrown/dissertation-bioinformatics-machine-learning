README

"Investigating Multidrug Resistance in Escherichia coli with Phylogenetics and Machine Learning" by David C. Brown, PhD

Descriptions for each of the appendices from the dissertation.

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

-----
-----

APPENDIX C: EXAMPLE RAxML SUBMISSION TO SLURM

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
