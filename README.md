## Bayesian Analysis of RCT Results
### C.V. Cosgriff

The [ANDROMEDA-SHOCK trial](https://jamanetwork.com/journals/jama/fullarticle/2724361) was recently published and has been a point of controversey. Despite results suggesting that capillary refill is safe, if not beneficial, when guiding treatment as compared to lactate level, the trial was deemed _negative_ based on the null-hypothesis testing framework that is standard across the current research literature.

A rich discussion ensued online and Dan Lane demonstrated a Bayesian analysis of the result [here](https://discourse.datamethods.org/t/andromeda-shock-or-how-to-intepret-hr-0-76-95-ci-0-55-1-02-p-0-06/1349/20) in `R` based on methods from [this paper](https://doi.org/10.1016/j.jclinepi.2008.07.006).

This notebook provides a `Python` implementation of Dan's code, examining the [ANDROMEDA-SHOCK trial](https://jamanetwork.com/journals/jama/fullarticle/2724361), and then applies the same approach to the [EOLIA trial](https://www.nejm.org/doi/full/10.1056/NEJMoa1800385). The latter has a more thorough Bayesian analysis published [here](https://www.ncbi.nlm.nih.gov/pubmed/30347031). The goal of this notebook is to provided clinicians keen on using this approach to interpret clinical trial results the requisite code.
