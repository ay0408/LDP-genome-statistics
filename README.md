# Genomic Statistical Analysis under Local Differential Privacy

This contains Python codes used in our experiments on local differentially private (LDP) methods for releasing genome statistics.
We employ the Randomized Response technique to satisfy LDP.

Our methods can be utilized in releasing key statistics in GWAS, e.g., chi^2-tests using a contingency table. Note that even if row/column sums are released at the same time, the privacy level will not change.

We focus on releasing statistics for an individual SNP at this time, but we plan to move forward with research to publish multiple statistics for many SNPs, including noise reduction and privacy evaluation.

The procedure to generate simulation data on genome statistics can be found in "Simulation Data" files.

"Accuracy" folder contains the experimental results on differences between the original and differentially private statistics.

In Supplements.pdf, we provide detailed discussion on the proposed methods and all experimental results.

## Important future directions

・Improving accuracy at cases of small ε. (e.g., utilizing the RAPPOR-based techniques or improving the EM algorithm or analyzing the recovered statistics in more detail)

・Extending our methods for the cases with two attribute data to more general cases, such as analyses using an M × N table.

## Note
Our paper entitled "Privacy-Preserving Genomic Statistical Analysis Under Local Differential Privacy" (https://doi.org/10.1007/978-3-031-37586-6_3) was presented at DBSec 2023.


In the paper, we also mention the case of assigning privacy budgets to each of two different attributes, e.g., genotype information and disease status, or row and column information of a contingency table.

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
