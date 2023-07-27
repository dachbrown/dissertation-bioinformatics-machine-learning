# dissertation-bioinformatics-machine-learning
Collection of materials from my dissertation research. "Investigating Multidrug Resistance in Escherichia coli with Phylogenetics and Machine Learning"

-----
-----

README

by David C. Brown - 20230727

This repository contains documents, presentations, and visualizations created for or derived from my dissertation research process.

Committee members included:
  -- Dr. Daniel Janies - CHAIR - djanies@charlotte.edu
  -- Dr. Jun-tao Guo           - jguo4@charlotte.edu
  -- Dr. Alex Dornburg         - adornbur@charlotte.edu
  -- Dr. Adam Reitzel          - adam.reitzel@charlotte.edu

Department of Bioinformatics and Genomics (BiG)
College of Computing and Informatics (CCI)
University of North Carolina at Charlotte

Many thanks to all who have helped me in my journey.

-----
-----

Dissertation Citation:

@phdthesis{
author={Brown,David C.},
year={2023},
title={Investigating Multidrug Resistance in Escherichia coli with Phylogenetics and Machine Learning},
journal={ProQuest Dissertations and Theses},
pages={120},
note={Copyright - Database copyright ProQuest LLC; ProQuest does not claim copyright in the individual underlying works; Last updated - 2023-06-22},
abstract={The next pandemic is already underway in the proliferation of antimicrobial resistance (AMR) genes that reduce the effectiveness of therapeutics. The lessened potency of these current drugs results in increased economic costs, higher public health burdens, and greater loss of life when attempting to manage these increasingly treatment resistant bacterial infections. Evolutionary principles guide this "silent pandemic", ultimately resulting in the development of superbugs, more formally described as multidrug resistant (MDR) bacteria. Such MDR phenotype bacteria resist three or more classes of antimicrobial compounds, representing significant obstacles to infection clearance and patient recoveries. To understand the forces driving the AMR pandemic, it is necessary to identify commonalities among bacterial genotypes with MDR phenotypes.This dissertation aims to uncover the genetic determinants of MDR bacteria through a study of Escherichia coli. One hypothesis for the development of MDR phenotype bacteria theorizes that resistance results from an increased number of mutations. Researchers refer to these highly mutable strains as possessing hypermutator phenotypes, often attributed to poorly functioning mismatch repair systems. One specific example of flawed mismatch repair in hypermutator bacteria was identified by LeClerc et al., 1996, defined as E. coli strains with a deficient Mutator S gene (gene mutS encodes the protein MutS).First, I analyzed the mutS genes from 817 high-quality E. coli isolates using phylogenetic comparative analyses. Although I observed 271 MDR isolates in this data set, I found no evidence for the existence of a deficient mutS gene as defined by LeClerc. Additionally, when modeling the coevolution of an MDR phenotype against all variant amino acid positions in the mutS gene, the evidence supports a largely independent evolution between MDR and the mutS mismatch repair gene.Next, to better understand this confounding result, I undertook a statistical analysis of the whole genome sequences (WGS) for all E. coli isolates. I used supervised machine learning to identify the genetic annotations that best predict the development of resistance to several classes of antimicrobial compounds: aminoglycosides, folate pathway antagonists, macrolides, tetracyclines, and other. The five trained random forest estimators achieved a mean ROC AUC of 0.87 ± 0.04 on 66 features, engineered from 5,511 annotated genes in the calculated E. coli pangenome. I determined that the top performing features did not include the mutS mismatch repair gene, further confirming the results of my first investigation. Instead, I found evidence that genes associated with horizontal gene transfer (HGT) best predict MDR phenotypes, an idea called into question by LeClerc et al., 1996.Finally, I examined the component annotations which comprised the most important engineered features. Interestingly, I found that resistance to a given class of antimicrobial treatments results from a unique and specific pattern of annotated genes that does not include commonly understood genetic determinants of resistance. MDR is best predicted, not by AMR genes themselves, but by accessory genes often involved in the horizontal and lateral transfer of genetic information. My investigation supports the current domain understanding, that horizontal gene inheritance mechanisms drive the proliferation of antimicrobial resistance, by indicating gene sets which predict resistance to specific categories of antimicrobial compounds.This work demonstrates the importance of combining phylogenetic methods and statistical modeling tools like machine learning to arrive at working hypotheses for polygenic traits. Additionally, this investigation portrays the research value of survey data. By identifying unique mechanisms for the continued proliferation of different resistance classes, this dissertation addresses the root evolutionary drivers of the AMR pandemic. In future, further investigation of the evolutionary history of the specific genes responsible may lead to new therapeutic targets or improved prescription strategies.},
keywords={Antimicrobial resistance; Escherichia coli; Machine learning; Multidrug resistance; Phylogenetics; Bioinformatics; Biostatistics; Artificial intelligence; Genetics; 0308:Biostatistics; 0715:Bioinformatics; 0800:Artificial intelligence; 0369:Genetics},
isbn={9798379438609},
language={English},
url={https://www.proquest.com/dissertations-theses/investigating-multidrug-resistance-em-escherichia/docview/2806816302/se-2},
}

-----
-----

This project is licensed under the CC-BY-4.0 License - see [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/) for details.
