# cupcake

This package contains routines to perform principal component analysis (PCA) using genome-wide association study (GWAS) summary statistics. The resultant **basis** is a lower-dimensional representation of input traits, that summarises their genetic relationships. The basis' main utility is the projection of other traits, especially those for which sample sizes are modest and conventional GWAS analyses are challenging. These projected traits can be used for the biological characterisation of existing components or as a vehicle for investigating the genetic architecture of clinically related traits.

# Installation (V1.0)

```
library(devtools)
install_github('ollyburren/cupcake@v1.0.0',build_vignettes=TRUE)
## for latest
## install_github('ollyburren/cupcake',build_vignettes=TRUE)
````

# Documentation

Please see online documentation and vignettes for common use cases [here](https://ollyburren.github.io/cupcake).
