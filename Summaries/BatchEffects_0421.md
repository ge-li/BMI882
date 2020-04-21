# AGene Set Enrichment Analysis

### [Leek et al. (2010)](https://doi.org/10.1038/nrg2825)

##### Title: Tackling the widespread and critical impact of batch effects in high-throughput data

##### Author(s): Leek et al.

In this paper, the authors discuss the batch effects in high-throughput data. These artifacts occur because measurements are affected by laboratory conditions, reagent lots and personnel differences, which can lead to erroneous conclusions if they are correlated with the outcome of interest. The authors examined multiple published studies to claim that batch effects are widespread. The authors provide experimental design solutions and statistical solutions to adjust for the confounding of batch effects.

One flaw of this paper is about not adjusting for multiple hypothesis testing in the susceptible features, which were determined by setting a 0.01 association p-values cutoff of features and surrogates. And in Fig. 1(c), I don't see the reason to connect the dots to compare the date-group difference. Otherwise, this article is pretty good. 

Questions:

1. Are most studies done after this work consider accounting for batch effects?
2. What're the differences between batch effects and the classic correlated unknown source of variation.