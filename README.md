# LDP-genome-statistics

This contains Python codes used in our experiments on local differentially private (LDP) methods to release genome statistics.
We employ the Randomized Response technique to satisfy LDP.

Our methods can be utilized in key statistical analyses in GWAS, e.g., chi^2-tests using a contingency table, family-based association studies,
and analyses considering correction for population stratification.

The procedure to generate simulation data on genome statistics can be found in the "Simulation Data" file.

"Accuracy" files contain the experimental results on differences between the original and differentially private statistics.

## Note

For details of our mechanisms, please see our paper entitled "Privacy-Preserving Genomic Statistical Analysis under Local Differential Privacy".


In the paper, we also mention the case where different privacy budgets are assigned to two different attributes, e.g., genotype information and disease status, or row and column information of a contingency table.

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
