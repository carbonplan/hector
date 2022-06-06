
Hector
======

![R-CMD](https://github.com/JGCRI/hector/workflows/R-CMD/badge.svg) | 
![Command Line Hector](https://github.com/JGCRI/hector/workflows/Command%20Line%20Hector/badge.svg) | 
![test-coverage](https://github.com/JGCRI/hector/workflows/test-coverage/badge.svg) | 
[![codecov](https://codecov.io/gh/JGCRI/hector/branch/master/graph/badge.svg?token=EGM0lXDxRv)](https://codecov.io/gh/JGCRI/hector) | 
![lint](https://github.com/JGCRI/hector/workflows/lint/badge.svg)

This is the repository for **Hector**, an open source, object-oriented, simple 
global climate carbon-cycle model that runs very quickly while still
representing the most critical global scale earth system processes. 
Hector is a simple climate model (SCM, also known as a reduced-complexity 
climate model), a class of models that are extremely versatile with a wide
range of applications. Due to their computational efficiency, SCMs can easily
be coupled to other models and used to design scenarios, emulate more complex 
climate models, and conduct uncertainty analyses.

## Installation 

The `hector` R package can be installed using the `remotes::install_github` 
function. More detailed installation instructions, including how to set up
Hector as a command line executable, can be found [here](articles/BuildHector.html).

```r
remotes::install_github('jgcri/hector')
library(hector)
```

## Tools and Software That Work with Hector

* [GCAM](https://github.com/JGCRI/gcam-core): Hector can be used as the climate component in [GCAM](http://jgcri.github.io/gcam-doc/)
* [pyhector](https://github.com/openclimatedata/pyhector): a Python
  interface to Hector
* [fldgen](https://github.com/JGCRI/fldgen): a spatially resolved temperature & precipitation emulator for CMIP5 ESMs
* [HectorUI](https://jgcri.shinyapps.io/HectorUI/): run Hector in a web interface!

## Contributing to Hector

 The Hector team welcomes and values community contributions, but please see 
 our [Contribution Guide](articles/ContributionsGuide.html) and note by  contributing 
to this project, you agree to abide to our [Contributor Code of Conduct](CODE_OF_CONDUCT.html)

 *** 
This research was supported by the U.S. Department of Energy, Office of Science, as part of research in Multi-Sector Dynamics, Earth and Environmental System Modeling Program. The Pacific Northwest National Laboratory is operated for DOE by Battelle Memorial Institute under contract DE-AC05-76RL01830.
