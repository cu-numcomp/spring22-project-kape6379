# Individual Project: LaplaceInterpolation.jl
This is a julia based package which executes fast interpolation on a grid. 
## Key Problems
Interpolation: this package focuses on fast interpolation execution on a grid in linear-time. Its goal is to expedite interpolation from one to three dimensions as opposed to the more commonly limited slower one to two dimension routines. 

## Stakeholders
This software was developed by Vishwas Rao, Charlotte L. Haley, and Mihai Anitescu. The work was in support by the U.S. Department of Energy as well as University of Chicago and the Argonne National Laboratory.  

It was implemented with the intention of creating a more efficent interpolation routine to fill missing data points within grids. It was intended to provide a less restrictive and fast means to run interpolation accross one to three dimensions. 

## Metrics and Features 
Using the Matern kernel interpolant the routine is drastically simplified in special cases. They state that it is considered fast becuase it arrives to a sollution of Ax = b. 

## Experiment
I think it would be interesting to experiment laplace interoplation on topographic surveys because it's interesting to see the graphs it produces.
