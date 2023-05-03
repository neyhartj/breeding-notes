# breeding-notes
Simple repository of links to tools for plant breeding and genetics, with some annotation. This is for information purposes only. 

## Mixed-models

A section on mixed-models. See my other repository on examples of [mixed-model applications](https://github.com/neyhartj/mixed_model_applications) for plant breeding experiments.

### R packages
+ [CRAN task view for mixed-models](https://cran.r-project.org/web/views/MixedModels.html)
+ [lme4](https://cran.r-project.org/web/packages/lme4/index.html)
    - Can be forced to fit compound symmetry, unstructured, and diagonal covariance structures
+ [glmmTMB](https://cran.r-project.org/web/packages/glmmTMB/index.html)
    - Allows for some cool covariance structures, including Toeplitz, AR1, spatial exponential; see [here](https://glmmtmb.github.io/glmmTMB/articles/covstruct.html)
+ [blme](https://cran.r-project.org/web/packages/blme/index.html)
    - Extends lme4 and allows for prior distributions; it also allows for the residual variance to be fixed (useful for two-stage analysis)
+ [rrBLUP]()
    - Very nice for a single random effect; the go-to for genomewide selection
+ [sommer](https://cran.r-project.org/web/packages/sommer/index.html)
    - Great for mixed models with multiple random effects and with kinship
+ [lme4GS](https://github.com/perpdgo/lme4GS)
    - lme4 language with flexibility for kinship; in theory the more complex covariance structures of lme4 (us, cs, diag) could be deployed
+ [asreml](https://vsni.co.uk/software/asreml-r)
    - The gold standard for quickly fitting models with complex covariance sturctures, but you need a license
+ [mmrm](https://cran.r-project.org/web/packages/mmrm/index.html)
    - Mixed-models for repeated measures; allows for time-dependent covariance structures like AR1, ante, toep, and exp
    
### Tutorials
    

## QTL mapping / GWAS

### R packages

+ The [Biometris](https://github.com/Biometris) group has several useful R packages:
    - [statgenGWAS](https://github.com/Biometris/statgenGWAS)
        - single-trait GWAS
    - [statgenQTLxT](https://github.com/Biometris/statgenQTLxT)
        - multi-trait, multi-environment GWAS
    - [statgenIBD](https://github.com/Biometris/statgenIBD)
        - Calculate identity-by-decent probabilities in two-, three-, and four-way crosses
        
### Tutorials

## GxE

### R packages

+ [statgenGxE](https://github.com/Biometris/statgenGxE)
    - Mega-environment analysis, stability, FW-regression, AMMI and GGE, etc. all the fun stuff
+ [statgenSTA](https://github.com/Biometris/statgenSTA)
    - Mixed-model analysis of field trials with or without spatial trends
    
### Tutorials


# Phenomics

# 
