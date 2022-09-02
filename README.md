# RH_manuscript
Code and data that support the manuscriot "RH: A genetic metric for measuring intra-host Plasmodium falciparum relatedness and distinguishing cotransmission from superinfection"

barcode_pos.txt -- A text file showing the position and assay number of each barcode site. 

SLP_KDG_RT_barcodes.xlsx -- Excel file with all the barcodes used in this study

barcode_statistic_final_paper.ipynb -- Example Analysis script for the barcode data

Cotx_simulation_threshold.json -- pre-generated results for TPR and FPR at different cotransmssion levels

cotx_simulation_files -- Relatedness maps for 24 SNP molecular barcode following cotransmisison. Generated using Cotransmission model code (https://github.com/weswong/Cotransmission)
The naming convention is:
cotx_barcode_{coi}_{alpha}_{mu}.txt

Not all files will have these fields. Files without either the alpha or mu fields used the default parameters.
