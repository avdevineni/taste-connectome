# taste-connectome

This repository contains Python code and files for analyzing taste pathways in the fly brain connectome, as described in our paper, "Connectomic analysis of taste circuits in Drosophila", by Walker, Peña-Garcia & Devineni. 
The initial version of the paper was posted on bioRxiv here: https://www.biorxiv.org/content/10.1101/2024.09.14.613080v1 
A revised version of the paper was published in Scientific Reports: https://www.nature.com/articles/s41598-025-89088-9

Code for connectome analysis described in the first version of the paper is contained in the notebook called "taste_connectome_analysis_Sept2024". 
Code for connectome analysis described in the final version of the paper is contained in the notebook called "taste_connectome_analysis_Dec2024".
Files needed to run this code include 4 csv.gz files with connectome data, 4 csv files with GRN lists, and a folder called "simulation" containing the results of brain simulations.
Note that all of these files and the simulation folder needs to be contained in the same folder as the notebook in order to run the code.
This code generates output csv files containing lists of second- and third-order neurons, which we have uploaded to a separate folder ("output_csvs"), as well as other output files that are not included here.

Brain simulations were performed using code in the separate notebook called "GRN_activation", which was adapted from code provided by Philip Shiu (see https://github.com/philshiu/Drosophila_brain_model).
