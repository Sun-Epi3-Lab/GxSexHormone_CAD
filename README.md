# GxSexHormone_CAD
Below is the code used to run sex stratified GxSex Hormone Interactions Analysis. 
The outcome variable for this analysis is CAD

```
# GEM version 1.4.2 was used
GEM \
--pfile $"LOCATION OF PGEN FILE" \
--pheno-file $"LOCATION OF PHENOTYPE FILE" \
--sampleid-name IID \
--pheno-name CAD \
--covar-names Age_enrolled PC1 PC2 PC3 PC4 PC5 PC6 PC7 PC8 PC9 PC10 \
--exposure-names Testosterone \
--output-style meta \
--robust 1 \
--missing-value NA \
--threads 16 \
--delim \0 \
--out $"LOCATION OF OUTPUT"
```

