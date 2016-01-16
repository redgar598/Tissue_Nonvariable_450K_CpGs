# Tissue_Invariable_450K_CpGs
Scripts and lists of CpGs which are seen as invariable in GEO data on the 450K

If you do this DON'T use Limma. And be carefule about p value distributions. Permutate the main effect variable to see if the p value distribution is unexpectedly skewed.  

## Examples

In a study of 25 blood samples Lisa used a 25th-75th reference range with 0.05 as the varability cutoff and found that ~108,000/114,000 blood invariable CpGs were invariable in here data aswell. So the cutoffs should agree with even more stringent varibility cutoffs. 

In PAWS (buccals) 99.5% of the buccal invariable CpGs are also invariable in PAWS
