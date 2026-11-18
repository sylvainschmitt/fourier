# Fourier
[![DOI](https://zenodo.org/badge/1087187932.svg)](https://doi.org/10.5281/zenodo.24336064)

Manuscript submitted to *Agricultural and Forest Meteorology* on the 26/11/18.

## Usage

**fourier** analyses rely on the quarto documents `index.qmd`,
`supplementary_note.qmd` and `cover_letter.qmd` that can be run with R and
associated environment defined with [renv](https://rstudio.github.io/renv/).

## Project

**fourier** includes:
- Manuscript and analyse of the data with associated documentation and
figures:
  - Manuscript: `index.qmd` and associated html
  - Supplementary note: `supplementary_note.qmd` and associated html
  - Cover letter: `cover_letter.qmd` and associated html
- All data in `data/`
- All figures in `figs/`
- R environment definition with
[renv](https://rstudio.github.io/renv/articles/renv.html) in `renv/` and
`renv/lock`
- R files (`.Rprofile`)
- Git and GitHub files (`.gitignore`)
- Project documentation (`README.md` , `NEWS.md` ,
`LICENSE`)

## Poeple

- Sylvain Schmitt, CIRAD
- Erwan Hingant, University of Picardie Jules Verne
- Jonathan Lenoir, CNRS

## Abstract

Quantifying how forest canopies buffer temperature fluctuations in the
understorey is central to our understanding of biodiversity responses to
anthropogenic climate change. However, existing metrics (i.e., the offset and
slope-equilibrium approaches linking microclimate to macroclimate) capture the
buffering effect of the canopy at a single, pre-defined timescale and cannot
separate daily from seasonal and interannual signals within the same temperature
time series. We introduce the Discrete Fourier Transform (DFT) as a tool for
decomposing paired microclimate–macroclimate temperature time series into a
harmonic spectrum with amplitude and phase per frequency, so that canopy
buffering can be decomposed and quantified, all at once, for any timescale. We
illustrate the approach with two case studies using subcanopy air and soil
temperature records paired with weather-station and ERA5-Land reanalysis
reference data. In the first case study, spectral decomposition isolated the
dominant 24-hour cycle and showed that forest canopies buffered daily
air-temperature fluctuations by 75.9–90.3% across sites, with forest soils
buffering mean temperature even more strongly than air near the ground. In the
second case study, the same framework was used to debias ERA5-Land reanalysis
data against a local and ground-truth reference weather station by comparing
amplitude spectra across frequencies, correcting both the overestimation of mean
temperature and the underestimation of short-term variability. By resolving
canopy buffering across multiple timescales within a single, noise-robust
framework and by enabling principled debiasing of macroclimate reference
products, the DFT approach that we tailored to microclimatic time series offers
a versatile addition to the microclimate ecologist's toolkit, complementing
rather than replacing existing offset and slope-equilibrium approaches.
