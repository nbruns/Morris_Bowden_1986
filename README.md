## Implementaion of Bowden and Morris 1986 cohort model
Implementation of Bowden and Morris 1986 from Winter 2023. 

Full citation:
Morris, J., & Bowden, W. (1986). A mechanistic, numerical model of sedimentation, mineralization and decomposition for marsh sediments. *Soil Science Society of America Journal*, 50, 996–1105.

Morris and Bowden 1986 is the original soil-cohort/soil-column model in salt marshes. Its further development reviewed in Vahsen et. al:
Vahsen, M. L., Todd-Brown, K. E. O., Hicks, J., Pilyugin, S. S., Morris, J. T., & Holmquist, J. R. (2024). Cohort Marsh Equilibrium Model (CMEM): History, Mathematics, and Implementation. Journal of Geophysical Research: Biogeosciences, 129(4), e2023JG007823. https://doi.org/10.1029/2023JG007823

I got interested in this model because it has both C and N dynamics. N dynamics would later be dropped from marsh cohort models. I also was interested in demonstrating how to implement soil-cohort models in R.

I've also included teaching demo I put together that for getting started with implementing dynamic models and soil column models in R, deSolve_demo.Rmd
