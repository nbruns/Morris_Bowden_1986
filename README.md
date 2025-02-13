## Implementaion of Bowden and Morris 1986 cohort model
This is an implementation of the model from Bowden and Morris 1986 I did in Winter 2023. 

Full citation:
Morris, J., & Bowden, W. (1986). A mechanistic, numerical model of sedimentation, mineralization and decomposition for marsh sediments. *Soil Science Society of America Journal*, 50, 996–1105.

This is the original cohort model in salt marshes, and its later development is nicely reviewed in Vahsen et. al:
Vahsen, M. L., Todd-Brown, K. E. O., Hicks, J., Pilyugin, S. S., Morris, J. T., & Holmquist, J. R. (2024). Cohort Marsh Equilibrium Model (CMEM): History, Mathematics, and Implementation. Journal of Geophysical Research: Biogeosciences, 129(4), e2023JG007823. https://doi.org/10.1029/2023JG007823

I got interested in this model because it has not only C but also N dynamics. N dynamics would later be dropped from marsh cohort models. I also was interested in demonstrating salt marsh cohort models in R and not the more common Matlab.

I've also included a script that has a nice teaching demo for getting started with implementing dynamic models in R, deSolve_demo.Rmd
