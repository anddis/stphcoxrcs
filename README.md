# stphcoxrcs
#### A Stata user-written command to check the proportional-hazards assumption after a Cox model using restricted cubic splines
#### Version 1.6 (2015-06-17)
---


### Description
`stphcoxrcs` checks the proportional-hazards assumption for one covariate of interest (binary or
   continuous) after fitting a model with `stcox`. In particular, `stphcoxrcs` models the natural
   logarithm of analysis time using restricted cubic splines transformations, which are interacted with the
   covariate specified in `varname`. A joint Wald (default) or likelihood ratio test of all the
   interaction terms is carried out to test the proportional-hazards assumption. Lastly, `stphcoxrcs`
   produces a graph of the time-varying hazard ratio.


### Installation
To install the last version submitted to the [Boston College Statistical Software Components (SSC)](https://ideas.repec.org/c/boc/bocode/s458073.html), type
```
ssc install stphcoxrcs
```
from within a web-aware Stata. Currently, version **1.6 (2015-06-17)** is available from the SSC.

### Authors
Andrea Discacciati, Viktor Oskarsson, and Nicola Orsini

Karolinska Institutet, Sweden
