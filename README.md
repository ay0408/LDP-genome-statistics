# LDP-genome-statistics

This contains Python codes used in our experiments on local differentially private (LDP) methods to release genome statistics.
We employ the Randomized Response technique to satisfy LDP.

Our methods can be utilized in releasing key statistics in GWAS, e.g., chi^2-tests using a contingency table.
We focus on releasing statistics for individual SNP at this time, but we plan to move forward with research to publish multiple statistics for many SNPs, including noise reduction and privacy evaluation.

The procedure to generate simulation data on genome statistics can be found in the "Simulation Data" file.

"Accuracy" files contain the experimental results on differences between the original and differentially private statistics.

In the Supplementary Material, we describe the key statistics in GWAS and briefly discuss the existing studies and thier problems. Then, we provide the proofs of our theorems and supplemental information on the proposed methods and experiments.

## Important future directions

・Improve accuracy at cases of small ε. (e.g., utilize the RAPPOR-based techniques or improve the EM algorithm or analyze the recovered statistics in more detail)

・Extend our methods for the cases with two attribute data to more general cases, such as analyses using an M × N table.

## Note

For details of our mechanisms, please see our paper entitled "Privacy-Preserving Genomic Statistical Analysis under Local Differential Privacy".


In the paper, we also mention the case where different privacy budgets are assigned to two different attributes, e.g., genotype information and disease status, or row and column information of a contingency table.

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
