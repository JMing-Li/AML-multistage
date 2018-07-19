# Code accompanying *Precision oncology for acute myeloid leukemia using a knowledge bank approach*

Gerstung *et al.*, _Nature Genetics_ **49**:332-340 (2017). http://dx.doi.org/10.1038/ng.3756

This repository contains all code used for running the analysis in the above manuscript. It was used and tested in `R-3.1.2`. 

The main code can be found in `doc/SupplementaryMethodsCode.R`. It was run in `R` using the command 

   > rmarkdown::render("SupplementaryMethodsCode.R")
   
Additional code chunks can be found in `code`, mainly for parallelising some heavy computations in an LSF environment. Code for the multistage calculator can be found in `aml-multistage`. Data is located in the `data` subfolder.
