[![Build Status](https://travis-ci.org/Alexander-Barth/HF-radar-assim-exercise.svg?branch=master)](https://travis-ci.org/Alexander-Barth/HF-radar-assim-exercise)


# HF-radar-assim-exercise

## Using Binder

Click on the "launch binder" icon to start the notebooks. Setting-up the working environement on the binder service can take a couple of minutes. Binder will automatically shut down user sessions that have more than 10 minutes of inactivity.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Alexander-Barth/HF-radar-assim-exercise/master?filepath=assim_exercise.ipynb)

## Setting-up your work environment

Required software:

* Julia available from https://julialang.org/downloads/. The exercise is tested with the versions 1.0, 1.3 and 1.4 of Julia (on Linux and Windows 10) and Mac OS should work too.

* Some Julia packages, which can be installed with these commands once you started Julia:

```julia
using Pkg
Pkg.add(PackageSpec(url="https://github.com/Alexander-Barth/GeoMapping.jl", rev="master"))
Pkg.add("NCDatasets")
Pkg.add("PyPlot")
Pkg.add("Interpolations")
Pkg.add("DataAssim")
Pkg.add("IJulia")
using PyPlot
using IJulia
notebook()
```
These commands will also install `matplotlib` and `jupyter`.
Confirm the installation of `jupyter` with conda.

## Exercise

* Get the code for the exercise:

```bash
git clone https://github.com/Alexander-Barth/HF-radar-assim-exercise.git
```

This create the folder `HF-radar-assim-exercise`

* [Quick introduction to Julia](Julia.md)

* [Exercise questions](https://alexander-barth.github.io/HF-radar-assim-exercise/slides/)


<!--  LocalWords:  assim caen sudo julia NetCDF PyPlot IJulia el cd
 -->
<!--  LocalWords:  mkdir wget emacs EOF setq alist jl dir
 -->
