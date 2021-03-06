# **mobsim_app** -- Simulation and visualization of biodiversity patterns across spatial scales using the `mobsim` R-package 

## Authors

*Katharina Gerstner, Felix May*

## Description

This is an interactive tool that aims to simulate and visualize multiple biodiversity patterns across spatial scales using the `mobsim` R-package. A **Thomas model** is used to simulate point pattern distributions of individual species. Key parameters of the simulation are:

* **total number of individuals**, 
* **total number of species**, 
* **the type of the species-abundance distribution (SAD)**,
* **parameters specific to the SAD type**, e.g. the coefficient of variation in the lognormal SAD determines the **eveness of the abundances** (the lower CV(abundance), the more even is the community),
* **spatial aggregation of species** given as the mean distance to mother points and either the number of mother points or clusters. The lower the mean distance to mother points the more clumped is the community.  Similarly, the smaller the number of mother points (minimum=1) or alternatively the larger the number of clusters the more clumped is the community.

The tool   
1. simulates locations of individuals of different species in a location (plot, area);      
2. plots biodiversity patterns such as   
+ species-abundance distributions (SAD) using Preston octave plot and rank-abundance curve,   
+ spatial distribution of individuals within a unit area,  
+ species accummulation curves (SAC), species-area relationships (SAR), and the distance-decay curve.   

## Source Code
https://github.com/MoBiodiv/mobsim_app

## License

GNU GPL




