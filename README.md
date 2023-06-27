WLAR -- A METHOD in finding driver genes from multi-omics data with R

copywrite by Wensu Liu, @ China Medical University
wsliu@cmu.edu.cn

WLAR is a method based on association rules algorithm and co-occurrence calculation to predict driver genes and interacted drugs for user required terms

Inputted file should be multi-omics datasheet (on format of .csv or .tsv)
Methylation data should be converted to beta-value expression data
Single cell transcriptome data should be converted to cluster expressions 

The first column should be converted into GENE SYMBOL, and guarantee no duplicate genes existing
The other colunmns should be expression value in either format, and column name should be samples

The output files include predicted driver genes and interacted drugs 