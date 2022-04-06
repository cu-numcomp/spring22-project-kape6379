# Individual Project: LaplaceInterpolation.jl
This is a julia based package which executes fast interpolation on a grid. It also features a python package and wrapper as well. 
## Key Problems
Interpolation: this package focuses on fast interpolation execution on a grid in linear-time. Its goal is to expedite interpolation from one to three dimensions as opposed to the more commonly limited slower one to two dimension routines. 

## Stakeholders
This software was developed by Vishwas Rao, Charlotte L. Haley, and Mihai Anitescu. The work was in support by the U.S. Department of Energy as well as University of Chicago and the Argonne National Laboratory.  

It was implemented with the intention of creating a more efficent interpolation routine to fill missing data points within grids. It was intended to provide a less restrictive and fast means to run interpolation accross one to three dimensions. 

## Metrics and Features 
Using the Matern kernel interpolant the routine is drastically simplified in special cases. They state that it is considered fast becuase it arrives to a sollution of Ax = b. 

The algorithmic complexity is considered as O(M) when using a matrix A on the laplace interpolation. They conclude that the big O constant is small.

They utilize the Matern kernel in the form below 

![Image 4-6-22 at 9 57 AM](https://user-images.githubusercontent.com/66287109/162017090-a9702861-fceb-49ff-aead-8c6687a9d8bd.jpg)


## Test
Running this package:
* Get pkg
```
pkg> add https://github.com/vishwas1984/LaplaceInterpolation.jl
```
* Clone the repository using https://github.com/vishwas1984/LaplaceInterpolation.jl.git into jupyter notebooks
* Navigate to /LaplaceInterpolation.jl/Notebooks
* Run julia and paste the following to begin tests
```
julia> using Pkg 
] activate . 
julia> Pkg.add(url="https://github.com/vishwas1984/LaplaceInterpolation.jl") 
julia> Pkg.instantiate()
julia> include("run_notebooks.jl")
```
Example test provided:
![Image 4-6-22 at 9 41 AM](https://user-images.githubusercontent.com/66287109/162014974-931e1f5e-d7b1-4a03-b0db-0d1bcac6e68e.jpg)
![Image 4-6-22 at 9 47 AM](https://user-images.githubusercontent.com/66287109/162015499-dbeedae7-8e61-494c-a9b5-61ef1816945e.jpg)

 ![monkey](https://user-images.githubusercontent.com/66287109/162015609-5263befd-73ea-43f8-9325-618e6ec5e6c4.png)


## Experiment
I think it would be interesting to experiment laplace interoplation on topographic surveys because it's interesting to see the graphs it produces using similar methods as the people in this project did. Adding holes to topographic surveys and interpreting what it means is definitely something that interests me. I was also looking into tricubic interpolation and wondering how the two could be combined. 
