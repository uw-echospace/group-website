---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "EchoPro workflow modernization"
date: 2022-01-25T17:02:36-08:00
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

The [Fisheries Engineering and Acoustics Technology (FEAT) team](https://www.fisheries.noaa.gov/west-coast/sustainable-fisheries/fisheries-engineering-and-acoustic-technologies-team) at the NOAA Fisheries [Northwest Fisheries Science Center (NWFSC)](https://www.fisheries.noaa.gov/about/northwest-fisheries-science-center) collaborates with [Fisheries and Oceans Canada (DFO) - Pacific Region](https://www.dfo-mpo.gc.ca/index-eng.htm) to estimate total biomass of [Pacific hake](https://www.fisheries.noaa.gov/species/pacific-whiting) by incorporating acoustic and biological trawl data from the [Joint U.S.-Canada Integrated Ecosystem and Pacific Hake Acoustic-Trawl Survey](https://www.fisheries.noaa.gov/west-coast/science-data/joint-us-canada-integrated-ecosystem-and-pacific-hake-acoustic-trawl-survey) (aka the "Hake survey").
These biomass estimates are the inputs for the stock assessment of hake and need to be completed in an efficient and timely manner after the survey. The biomass estimates are currently produced by a suite of Matlab scripts operated by a single user, and the analysis procedures are not easily adaptable by other FEAT/DFO team members. The central objective of this project is to provide a well-documented open-source Python software package that contains the core computational functionality of the current Matlab EchoPro program and provides basic visualization of the analysis results. The new software package will contain an Application Programming Interface (API) that can be invoked in a reproducible manner and can accept configuration of key analysis parameters and other run-time setups via a machine and human-readable configuration file.

**Funding agency**: NOAA Fisheries, NOAA NWFSC
