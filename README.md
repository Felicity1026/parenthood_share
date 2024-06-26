# parenthood_share

R codes for "A phenome-wide spectrum of morbidity and mortality risks related to parenthood among 0.5 million Chinese men and women" by Meng Xiao.



Details:
1. PheWAS example for ramdon seeds and PheWAS analysis in China Kadoorie Biobank (CKB) cohort study comprising 0.5 million adults.
2. Morbidity risk of hypertension among participants without hypertension using Cox regression with age as the time scale. The analysis of other diseases is similar to this.
3. Mortality risk of participants with hypertension using Cox regression with age as the time scale. The analysis of other diseases is similar to this.
4. Details of CKB participants (Table 1).
5. Restricted cubic spline for associations between the number of children and mortality risks among male and female patients with any of the 26 diseases at baseline in CKB cohort study.



Overview of PheWAS:
Packge PheWAS provides methods for the creation of PheWAS phenotypes, analysis, and plotting.While these methods are designed primarily for genetics based PheWAS analysis, they can perform GWAS or even phenotype only studies.

System Requirements:
Packge PheWAS requires only a standard computer with enough RAM to support the in-memory operations.

Software requirements:
This package is supported for Windows and Linux. 

Installation Guide:
install.packages("devtools")
install.packages(c("dplyr","tidyr","ggplot2","MASS","meta","ggrepel","DT"))
devtools::install_github("PheWAS/PheWAS")

Other details for PheWAS could be found in the PheWAS example for ramdon seeds and PheWAS analysis in China Kadoorie Biobank (CKB) cohort study.




