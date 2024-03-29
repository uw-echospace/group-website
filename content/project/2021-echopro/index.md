---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "EchoPro workflow modernization"
date: 2024-03-28T17:02:36-08:00
authors: 
slug: 2021-echopro
weight: 17
draft: false
tags: 
  - fisheries acoustics
  - biomass estimation
  - community engagement
  - software development
summary: "Modernizing the EchoPro workflow for integrating acoustic and biological survey samples for biomass estimation."

# Customize
share: false
markup: md
math: true
featured: false

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  caption:
  Placement options: 1
  focal_point: "Center"
  preview_only: true

---

The [Fisheries Engineering and Acoustics Technology (FEAT) team](https://www.fisheries.noaa.gov/west-coast/sustainable-fisheries/fisheries-engineering-and-acoustic-technologies-team) at the NOAA Fisheries [Northwest Fisheries Science Center (NWFSC)](https://www.fisheries.noaa.gov/about/northwest-fisheries-science-center) collaborates with [Fisheries and Oceans Canada (DFO) - Pacific Region](https://www.dfo-mpo.gc.ca/index-eng.htm) to estimate total biomass of [Pacific hake (<i>Merluccius productus</i>)](https://www.fisheries.noaa.gov/species/pacific-whiting) by incorporating acoustic and biological trawl data from the [Joint U.S.-Canada Integrated Ecosystem and Pacific Hake Acoustic-Trawl Survey](https://www.fisheries.noaa.gov/west-coast/science-data/joint-us-canada-integrated-ecosystem-and-pacific-hake-acoustic-trawl-survey) (aka the "Hake survey").

These biomass estimates are the inputs for the stock assessment of hake and need to be completed in an efficient and timely manner after the survey. The biomass estimates are currently produced by a suite of Matlab scripts operated by a single user, and the analysis procedures are not easily adaptable by other FEAT/DFO team members. The central objective of this project is to provide a well-documented open-source [Python software package](https://github.com/OSOceanAcoustics/echopop) (`echopop`) that contains the core computational functionality of the current Matlab EchoPro program and provides basic visualization of the analysis results. 

The new software package will contain an expanded [documentation](https://echopop.readthedocs.io/en/latest/) that details the underlying theory and algorithmic implementation that help facilitate reproducibility. Other features include an [Application Programming Interface (API)](https://echopop.readthedocs.io/en/latest/api.html) that can be invoked in a reproducible manner, a flexible analysis configuration that allows for both machine and human-readable parameterizations, and interactive Jupyter notebooks that exemplify various workflows such as constructing a [mesh grid for kriging](https://github.com/OSOceanAcoustics/echopop/blob/main/example_notebooks/kriging_mesh_walkthrough.ipynb) or [report generation](https://github.com/OSOceanAcoustics/echopop/blob/main/example_notebooks/reports_workflow.ipynb).

**Funding agency**: NOAA Fisheries, NOAA NWFSC


**Funding agency**: NOAA Fisheries, NOAA NWFSC
