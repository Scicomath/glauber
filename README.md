# Optical Glauber model in heavy ion collision
Glauber model is used to calculate the number of participating nucleons(N_part) and binary nucleon-nucleon collisions(N_coll). This can be combined with experiment data to classify collision events by collision centrality(impact parameter b), thus offer an oppotunity to compare theory calculation with experiments.

There are two types of glauber model, one is optical model which use optical-limit approximation, another one is Monte Carlo approach. Here we focus on the optical model, for Monte Carlo code, you can go to [jbernhard/glauber-model](https://github.com/jbernhard/glauber-model). For literature review, see [Miller, M. L., Reygers, K., Sanders, S. J., & Steinberg, P. (2007). Glauber Modeling in High-Energy Nuclear Collisions. Annual Review of Nuclear and Particle Science, 57(1), 205–243.](https://doi.org/10.1146/annurev.nucl.57.090506.123020)

## Aim
The aim of this code is to:
 - Calculate N_part and N_coll given impact parameter b
 - Calculate average impact parameter b for given centrality
 
## Input
The input of Glauber model is:
 - Charge distribution of nucleus
 - Inelastic nucleon-nucleon cross section

The charge distribution of nucleus is often get from elastic electron scattering experiment. See reference [H. De Vries, C.W. De Jager, C. De Vries, Nuclear charge-density-distribution parameters from elastic electron scattering, Atomic Data and Nuclear Data Tables, Volume 36, Issue 3, 1987, Pages 495-536, ISSN 0092-640X](http://faculty.virginia.edu/ncd/dldata/1987_source.pdf) for details.
## Usage
to be continue...
