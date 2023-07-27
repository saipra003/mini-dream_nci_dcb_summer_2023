# mini-dream_nci_dcb_summer_2023
Code for mini-DREAM challenge from NCI DCB Summer 2023 Program.
Code was developed for presentation of group LabRats (Camille Kutter, Ethan Cohen, Sai Manikonda) at the NCI DCB mini-DREAM program final presentation.

All analyses on this file were run in R, using an R markdown script and in R studio. An HTML document of the final notebook was rendered. 

## The Challenge 
### Background
The file `MDA-PCa-2b control vs enzaR DifferentialExpression.csv` contains differential expression data for MDA Pca-2b (African American Prostate Cancer cell line) that has been treated with an androgen inhibitor enzalutamide. It is assumed that after the treatment period the cells in the treated condition are *resistant* to enzalutaminde.

After the treatment, the cells from the control (untreated) and experimental (treated) conditions underwent bulk RNA-seq.

### Your Objective
You are given a DESeq2 differential expression file that contains information about the relative expression of the genes in each experimental condition. The .xlsx file contains the data along with some additional information, while the .csv file contains only the data. Given this data, can you identify the top druggable genes or pathways that contribute to resistance in MDA Pca-2b.

### File Organization
All the analysis files and output are located in the `analysis` folder. All the original data is locted in the `data` folder. To make everyone's life easier I went ahead and converted the data portion of the `.xlsx` to a `.csv` file to help with importing data properly.