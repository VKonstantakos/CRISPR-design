# CRISPR-design
List of software/websites/databases/reviews for CRISPR gene editing.

This collection is inspired by [awesome-CRISPR](https://github.com/davidliwei/awesome-CRISPR).

## Overview

![Overview](https://ars.els-cdn.com/content/image/1-s2.0-S2001037019303551-ga1_lrg.jpg)

## Contents

- On-target prediction algorithms
- Off-target prediction algorithms
- Genome editing outcome predictions
- Databases
- Reviews

## On-target prediction algorithms (Machine Learning based)

- [SSC](http://cistrome.org/SSC/) - [webserver] - A sequence model for predicting sgRNA efficiency in CRISPR/Cas9 knockout experiments.
- [CRISPRscan](http://www.crisprscan.org) - [webserver] - A novel algorithm to predict gRNA efficiency in zebrafish.
- [WU-CRISPR](http://crispr.wustl.edu) - [webserver] - A web tool to design gRNA for CRISPR/Cas9 Knockout system (replaced by sgDesigner).
- [CRISPOR](http://crispor.tefor.net/) - [webserver] - A program that helps to design, evaluate and clone guide sequences for the CRISPR/Cas9 system.
- [TSAM](https://github.com/penn-hui/TSAM) - [Python, MATLAB, webserver] - Two-Step-Averaging-Method (TSAM) by averaging the predicted efficiency scores of a boosting algorithm and those by a support vector machine (SVM).
- [sgDesigner](https://github.com/wang-lab/sgDesigner) - [Perl/Python, [webserver](http://crispr.wustl.edu.)] - A stacking model framework using XGBoost, SVM and Logistic Regression as classifiers.


## On-target prediction algorithms (Deep Learning based)

- [DeepCRISPR](https://github.com/bm2-lab/DeepCRISPR) - [Python, webserver] - A deep learning based prediction model for sgRNA on-target knockout efficacy and genome-wide off-target cleavage profile prediction.
- [DeepCas9](https://github.com/lje00006/DeepCas9) - [R] - DeepCas9 tool can be used to make CRISPR sgRNAs activity prediction based on convolutions neural networks and a one-hot representation of DNA sequence.
- [CRISPRLearner](https://github.com/pierclgr/CRISPRLearner) - [Python] - A deep learning based system to predict CRISPR/Cas9 on target cleavage efficiency with 10 different model weights.
- [CNN-SVR](https://github.com/Peppags/CNN-SVR) - [Python] - A merged CNN as the front-end for extracting gRNA and epigenetic features as well as an SVR as the back-end for regression and predicting gRNA cleavage efficiency.


## Off-target prediction algorithms

- [CasFinder](http://arep.med.harvard.edu/CasFinder/) - [Python] - An algorithm for identifying specific Cas9 targets in genomes.
- [CasOT](http://casot.cbi.pku.edu.cn/) - [webserver] - A tool to find potential off-target sites in any given genome or user-provided sequence, with user-specified types of the protospacer adjacent motif, and the number of mismatches allowed in the seed and non-seed regions.
- [Cas-OFFinder](http://www.rgenome.net/cas-offinder/) - [webserver] - An algorithm that searches for potential off-target sites of Cas9 RNA-guided endonucleases.
- [CCtop](https://crispr.cos.uni-heidelberg.de) - [webserver] - An algorithm to predict CRISPR/Cas9 target.
- [CHOPCHOP](http://chopchop.cbu.uib.no/index.php) - [webserver] - A web tool for selecting target sites for CRISPR/Cas9, CRISPR/Cpf1.
- [CRISPR RGEN Tools](http://www.rgenome.net) - [webserver] - An algorithm can identify of RGEN off-target sites without limitation by the number of mismatches and allow variations in PAM sequences recognized by Cas9. Meanwhile, it can search for RGEN targets with low potential off-target effects and high knock-out efficiencies in the exon region.
- [CRISPRTarget](http://bioanalysis.otago.ac.nz/CRISPRTarget/crispr_analysis.html) - [webserver] - A tool to explore the targets of CRISPR RNAs.
- [flyCRISPR](http://targetfinder.flycrispr.neuro.brown.edu) - [webserver] - Specificity for Drosophila to find CRISPR target sites and evaluate each identified CRISPR target.
- [Geneious CRISPR Site Finder](https://www.geneious.com/academic/) - [software] - It searches for off-target binding sites against a database of sequences.
- [GT-Scan](https://gt-scan.csiro.au/) - [webserver] - A flexible web-based tool that ranks all potential targets in a user-selected region of a genome in terms of how many off-targets they have.
- [GT-Scan2](https://github.com/BauerLab/GT-Scan2) - [R] - It is Chromatin- and Transcription-aware target site optimization tool for CRISPR/CAS9.
- [sgRNAcas9](http://www.biootools.com/) - [software] - A software package that can be applied to search rapidly for CRISPR target sites, and analyze the potential off-target cleavage sites of CRISPR-Cas9 simultaneously.
- [WGE](https://www.sanger.ac.uk/htgt/wge/) - [webserver] - A algorithm shows CRISPR sites (paired or single) in and around genes and scores the pairs for potential off-target sites, and browse individual and paired CRISPR sites across human, mouse.

## Genome editing outcome predictions

- [FORECasT](https://partslab.sanger.ac.uk/FORECasT) - [Python, webserver] - A method to predict and view mutational profiles for individual gRNAs.
- [inDelphi](https://www.crisprindelphi.design) - [webserver] - A computational model that predicts the heterogeneous (100+ unique) mixture of indels resulting from microhomology-mediated end-joining (MMEJ) and non-homologous end-joining (NHEJ) at a CRISPR-induced cut. inDelphi synthesizes known biological mechanisms of DNA repair with machine learning and achieves strong accuracy.
- [Lindel](https://lindel.gs.washington.edu/Lindel/) - [webserver] -  A Logistic regression model for accurate indel prediction induced by Cas9 cleavage. [NAR 2019](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz487/5511473)
- [Microhomology-Predictor](http://www.rgenome.net/mich-calculator/) - [webserver] - A web tool can simply predict the mutation patterns caused by microhomology-mediated end joining (MMEJ) and estimate how frequently unwanted in-frame deletions would happen.
- [SPROUT](https://zou-group.github.io/SPROUT) - [webserver] - A machine learning algorithm to predict the repair outcome of a CRISPR-CAS9 knockout experiment. Trained in primary human T cells, SPROUT may facilitate design of SpCas9 guide RNAs in therapeutically important primary human cells.


## Databases

- [BioGRID ORCS](https://orcs.thebiogrid.org) - [webserver] - An open repository of CRISPR screens compiled through comprehensive curation efforts. Paper: [Nucleic Acids Research 2019](https://www.ncbi.nlm.nih.gov/pubmed/30476227)
- [DepMap](https://depmap.org/portal/) - [webserver] - A comprehensive reference map of the Cancer Dependency Map project at the Broad Institute. Paper: [Cell 2017](https://www.ncbi.nlm.nih.gov/pubmed/28753430)
- [GenomeCRISPR](http://genomecrispr.dkfz.de) - [webserver] - A database for high-throughput CRISPR/Cas9 screening experiments.
- [PICKLES](https://hartlab.shinyapps.io/pickles/) - [webserver] - A database of pooled in-vitro CRISPR knockout library essentiality screens.
- [Project Drive](https://oncologynibr.shinyapps.io/drive/) - [webserver] - A Compendium of Cancer Dependencies and Synthetic Lethal Relationships Uncovered by Large-Scale, Deep RNAi Screening. Paper: [Cell 2017](https://www.ncbi.nlm.nih.gov/pubmed/28753431).
- [Project Score (Sanger DepMap)](https://score.depmap.sanger.ac.uk/) - [webserver] - Genome-scale CRISPR–Cas9 screens in 324 human cancer cell lines from 30 cancer types. Paper: [Nature 2019](https://www.ncbi.nlm.nih.gov/pubmed/30971826).

## Reviews
- 2018 - Doench - [Am I ready for CRISPR? A user's guide to genetic screens.](https://www.ncbi.nlm.nih.gov/pubmed/29199283)
