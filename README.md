# Multi-omics-and-Electrophysiological-Examination-of-GABAA-Receptors-in-the-DLPFC-of-Humans-w-AUD
Codes describing methods for Euclidian distance analysis/reorganization of multi-omic data and power analyses. 
===========================================================
Characterization of GABAAR in the DLPFC of humans with AUD
===========================================================

This project aims to characterize the electrophysiological function and multi-comic profile of GABA-A receptors (GABAAR) in the dorsolateral prefrontal cortex (DLPFC) of individuals with alcohol use disorder (AUD). To complete our multi-omic analysis, we systematically analyzed RNA sequencing data, label-free proteomics of regional tissue, and label-free proteomics of isolated synaptosomes collected from human postmortem DLPFC brain samples from AUD individuals.

We completed a Euclidian distance analysis/reorganization analysis using expression data from our transcriptomic and proteomic data sets. 

Code outline from Supplementary data 1-10 produces dendrograms of AUD and Control samples GABAAR subunit expression data to visualize changes in expression patterns, creates and saves heatmaps of gene expression of each sample in each group, calculates euclidian distance matrix with consensus to controls (EDMCC)and charts the correlations of each samples to the EDMCC, Completes proper statistical testing to compare correlations, graphs results to a violin plot. 



Supplementary Data 1. R Code for Euclidian distance analysis/transcriptomic reorganization of GABAAR subunits. An .Rmd file containing the code.  

	- ‘AUD data 1.xlsx’. Data used to complete Euclidian distance analysis/transcriptomic 	reorganization of GABAAR subunits. Contains a matrix of samples and with their expression levels of each of the 19 GABAAR subunits observed in the RNA sequencing data.

	- ‘AUD data 2.xlsx’. Data used to complete Euclidian distance analysis/transcriptomic reorganization of GABAAR subunits. Contains a transposed matrix of the data from ‘AUD data 1.xlsx’.



Supplementary Data 4. R Code for Euclidian distance analysis/proteomic reorganization of GABAAR subunits An .Rmd file containing the code. 

	- ‘Prot GABAAR Subunits 1.xlsx’.  Data used to complete Euclidian distance analysis/proteomic reorganization of GABAAR subunits. Contains a matrix of samples and with their expression levels of each of the 7 GABAAR subunits observed in the label-free proteomic data. 

	- ‘Prot GABAAR Subunits 2.xlsx’.  Data used to complete Euclidian distance analysis/proteomic reorganization of GABAAR subunits. Contains a transposed matrix of the data from ‘Prot GABAAR Subunits 1.xlsx’.



Supplementary Data 7. R Code for Euclidian distance analysis/synaptoproteomic reorganization of GABAAR subunits. An .Rmd file containing the code.  

	-‘SynProt GABAAR Subunits 1’. Data used to complete Euclidian distance analysis/synaptoproteomic reorganization of GABAAR subunits. Contains a matrix of samples and with their expression levels of each of the 6 GABAAR subunits observed in the label-free proteomic data from isolated synaptosomes. 

	- ‘SynProt GABAAR Subunits 2’. Data used to complete Euclidian distance analysis/proteomic reorganization of GABAAR subunits. Contains a transposed matrix of the data from ‘SynProt GABAAR Subunits 1’. 



Supplementary Data 10. R Code for Euclidian distance analysis/synaptoproteomic reorganization of GABAAR trafficking proteins An .Rmd file containing the code. 

	- ‘SynProt GABAAR traffic 1’.  Data used to complete Euclidian distance analysis/synaptoproteomic reorganization of GABAAR trafficking proteins. Contains a matrix of samples and with their expression levels of each of the 7 GABAAR trafficking proteins observed in the label-free proteomic data from isolated synaptosomes. 

	- ‘SynProt GABAAR traffic 2’.  Data used to complete Euclidian distance analysis/synaptoproteomic reorganization of GABAAR trafficking proteins. Contains a transposed matrix of the data from ‘SynProt GABAAR traffic 1’.



During our power analyses, if data exhibited non-normal distribution, we used Supplementary data 13 which implemented the R ‘cliff.delta’ function using the ‘effsize’ package to calculate Cliff’s delta. All data used to complete this code for our project is written within the code

Supplementary data 14 estimates effect size by converting Cliff’s delta into a probability of superiority and then transforming that value into a Z-score. This Z-score is scaled into Cohen’s d. All data used to complete this code for our project is written within the code

 



