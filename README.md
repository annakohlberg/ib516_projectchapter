# thesis work for IB 516
working project on developing code &amp; organizational structure for chapter two of my thesis: *Using Passive Acoustic Monitoring to Map Biodiversity in the Pacific Northwest*

## project workflow
![project workflow](figures/ORTWS_Poster.png)

## objectives
the forested ecosystems of the pacific northwest contain some of the oldest, largest trees on earth and are home to a suite of species that depend on theses structures for all or part of their life history...

## organization of repo
there are four folders available that contain **data**, **code**, **figures** and other relavant material for this project

- the [data](data) folder holds the necessary data needed to run analyses

- the [code](code) folder contains x, y, z which pertain to x, y, and z things

- the [figures](figures) folder has the chapter's figures and scripts used to generate them

- the [manuscript](manuscript) folder has a copy of the working manuscript for this thesis chapter 

## joint species distribution model (jSDM)
i will be performing a [jSDM in R](https://cran.r-project.org/web/packages/jSDM/vignettes/jSDM.html) using the binomial probit in the long format, where

**ecological process:**
$$y_{ij} = Bernoulli(\theta_{ij})$$
