# MultipleScatteringLearnMoments


A Julia library for learning the radius and concentration of a material by using the moments of simulated backscattered waves. The backscattered waves are generated by the [MultipleScattering](https://github.com/jondea/MultipleScattering.jl) julia package
 
## Dependencies
You will need to add the following packages
```
julia
Pkg.add("StatsBase")
Pkg.add("JLD")
Pkg.add("GLMNet")
Pkg.add("Plots")
Pkg.add("LaTeXStrings")
```
and also clone the MultipleScattering package

```
Pkg.clone("https://github.com/jondea/MultipleScattering.jl.git")
```

## Get started
This package is tested and works for Julia 0.6 and 0.5.

To get started, download and include the library
```julia
Pkg.clone("https://github.com/gowerrobert/MultipleScatteringLearnMoments.jl")
using MultipleScattering
using MultipleScatteringLearnMoments

```

## Simple example
Use jupyter notebook to run the first demo  
```
jupyter notebook
demo_L2.ipynb
```

## More examples

To generate the regularization parameter lambda and the kernel parameters using crossvalidation, run 
```
jupyter notebook
cross_valid.ipynb
```

## Acknowledgements and contributing

For a reference and further reading see:
```
Learning about random media from near-surface backscattering:
using machine learning to measure particle size and concentration.
Artur L Gower,  Robert M Gower, Jonathan Deakin,  William J Parnell, and I. David Abrahams
```
