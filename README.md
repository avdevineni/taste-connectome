# taste-connectome

This repository contains Python code and files for analyzing taste pathways in the fly brain connectome, as described in our forthcoming preprint, "Connectomic analysis of taste circuits in Drosophila", by Walker, Peña-Garcia et al.

The main code for connectome analysis is contained in the notebook called "taste_connectome_analysis_Sept2024". 
Files needed to run this code include 4 csv.gz files with connectome data, 4 csv files with GRN lists, and a folder called "simulation" containing the results of brain simulations.
Note that all of these files and the simulation folder needs to be contained in the same folder as the notebook. 
This code generates output csv files containing lists of second- and third-order neurons, which we have uploaded to a separate folder ("output_csvs").

Brain simulations were performed using code in the separate notebook called "GRN_activation", which was adapted from code provided by Philip Shiu (see https://github.com/philshiu/Drosophila_brain_model).
