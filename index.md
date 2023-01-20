---
title: Sen Research Group Resources
---

## Software
- [BulkLMM.jl](https://github.com/senresearch/BulkLMM.jl) Julia
  package for performing a large number of univariate linear mixed
  model genome scans; suitable for eQTL analysis and genome scans with
  high-throughput phenotypes (Zifan Yu, Gregory Farage, Chelsea
  Trotter, Hyeonju Kim, Saunak Sen)
- [GeneNetworkAPI.jl](https://github.com/senresearch/GeneNetworkAPI.jl)
  Julia interface to the GeneNetwork API (Chelsea Trotter, Gregory
  Farage, Saunak Sen)
- [MatrixLMnet.jl](https://github.com/senresearch/MatrixLMnet.jl)
  Julia package for elastic net penalized matrix linear models (Jane Liang,
  Gregory Farage, Chenhao Zhao)
- [MatrixLM.jl](https://github.com/senresearch/MatrixLM.jl) Julia
  package with core functions for matrix linear models (Jane Liang,
  Gregory Farage, Chenhao Zhao)
- [Helium.jl](https://github.com/senresearch/Helium.jl) A fast and
  flexible Julia tabular serialization format (Gregory Farage)
- [GeneticScreens.jl](https://github.com/senresearch/GeneticScreens.jl)
  Julia package for analysis of high-throughput genetic screens (Jane
  Liang)
- [FlxQTL.jl](https://github.com/senresearch/FlxQTL.jl) Julia package for
  multivariate LMMs for structured traits (Hyeonju Kim)
- [LiteQTL.jl](https://github.com/senresearch/LiteQTL.jl) Julia package
  for eQTL scans using GPUs (Chelsea Trotter)
- [FastLMM.jl](https://github.com/sens/FastLMM.jl) Julia package for
  univariate LMMs (Saunak Sen)
- [R/lcest](https://github.com/senresearch/lcest) R package for
  estimation for bivariate left-censored data (Emily Hanson)

## Teaching resources
- [BIOE805 - R for Biostatistics - I](https://senresearch.github.io/bioe805)
  Introductory R course (Gregory Farage and Saunak Sen)
- [BIOE806 - R for Biostatistics - II](https://senresearch.github.io/bioe806)
  Second R course (Gregory Farage and Saunak Sen)
- [BIOE720 - Biostatistics for Public Health](https://senresearch.github.io/bioe720)
  Introductory Biostatistics using Stata
- [Julia introductory workshop](https://github.com/senresearch/julia-intro-docs)
  Materials from a workshop introducing Julia (Gregory Farage, Chelsea
  Trotter and Saunak Sen)
- [Webinar Series - Quantitative Genetics Tools for Mapping Trait Variation to Mechanisms, Therapeutics, and Interventions](https://opar.io/training/osga-webinar-series-2020.html) Webinar series organized by the NIDA Center of Excellence in Omics, Systems Genetics, and the Addictome (Saunak Sen, Laura Saba, Rob Williams and others)

## Visualizations

Some visualizations of statistical and computational concepts using
Pluto.jl notebooks.  These use Binder, and are a bit slow to start.
Please be patient!

### Diagnostic tests

- [Diagnostic tests: prevalence, sensitivity, specificity, and predictive values](http://notebooks.one/disease-testing.html)  How the postive/negative predictive values of a diagnostic test
   based on a quantitative measurement behave.
- [Diagnostic test with a varying cutoff](http://notebooks.one/roc.html) Shows how varying the cutoff point for a quantitative diagnostic
  test can affect sensitivity and specificity.

### Probability and simulations

- [Coin flip simulator](http://notebooks.one/flips.html) Simulates what
would happen if you flipped a coin a bunch of times, and kept a
running tally of the proportion of heads.
- [Common distributions](http://notebooks.one/distributions.html)
Simulator of common probability distributions as you vary the
parameters of those distributions.
- [Central Limit Theorem](http://notebooks.one/clt.html) Illustrates the
Central Limit Theorem by visualizing the histogram of the sample mean
for different distribution and sample sizes.
- [Probability rules and Bayes Theorem](http://notebooks.one/bayes.html)
Graphical illustration of Bayes Theorem.

### Power and sample size

- [How power depends on effect size, sample size, and the desired false
positive rate](http://notebooks.one/power .html) Interactive
visualization of impact of effect size and sample size on power.

### Optimization techniques

- [How the L1-penalty achieves
sparsity](http://notebooks.one/L1-penalty.html) Illustration of how
minimizing a quadratic loss function with an L1 penalty helps acheive
sparsity.

- [How the proximal operator works](http://notebooks.one/prox.html)
Illustration of the proximal operator used in optimization.
  
