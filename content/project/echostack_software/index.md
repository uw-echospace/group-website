---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "The open-source \"Echostack\" for flexible and scalable echosounder data processing"
date: 2021-07-01
authors: 
slug: echostack
weight: 15
draft: false
tags: 
  - fisheries acoustics
  - cloud computing
  - open-source
  - community engagement
summary: "Enhancing the processing capacity and efficiency for echosounder data."

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

[Water column sonar data collected by echosounders](https://storymaps.arcgis.com/stories/e245977def474bdba60952f30576908f) are essential for fisheries and marine ecosystem research, enabling the detection, classification, and quantification of fish and zooplankton from many different ocean observing platforms. However, the broad usage of these data has been hindered by the lack of modular software tools that allow flexible composition of data processing workflows that incorporate powerful analytical tools in the scientific Python ecosystem.

We address this gap by developing **Echostack**, a suite of open-source Python software packages that leverage existing distributed computing and cloud-interfacing libraries to support intuitive and scalable data access, processing, and interpretation. These tools can be used individually or orchestrated together, which we demonstrate in example use cases for a fisheries acoustic-trawl survey.

Below is a summary of the Echostack package:
<p align="center">
  <img src="echostack_summary.png" alt="Echostack summary" style="width:1000px"/>
  <b>Bat call activity detected in two UBNA sites in 2022.</b>
</p>

For more information, check out each of the code repositories:
- [Echopype](https://github.com/OSOceanAcoustics/echopype): performs data standardization and computation from raw instrument files to acoustic data products
  - Check out the [Echopype paper in ICES Journal of Marine Science](https://doi.org/10.1093/icesjms/fsae133)
- [Echopop](https://github.com/OSOceanAcoustics/echopop): generates acoustically derived biological estimates, such as abundance
  - Learn more on the [Echopop project page](../../project_others/echopop/)
- [Echoshader](https://github.com/OSOceanAcoustics/echoshader): enables interactive acoustic data visualization and exploration
- [Echoregions](https://github.com/OSOceanAcoustics/echoregions): interfaces acoustic data with machine learning developments
- [Echodataflow](https://github.com/OSOceanAcoustics/echodataflow): workflow orchestration via text-based configuration “recipes” instead of code

These packages are accompanied by a set of data processing level definitions, [Echolevels](https://github.com/OSOceanAcoustics/echolevels), which categorizes data products at different workflow stages to enhance data understanding and provenance tracking.


Check out Wu-Jung's talk at SciPy 2024 and the associated [paper](https://doi.org/10.25080/WXRH8633) in the proceedings!
{{< youtube YRFxMGisGww >}}

**Funding**: 
- NOAA Fisheries
- NOAA Office of Ocean Exploration and Research [FY2021 grants](https://oceanexplorer.noaa.gov/news/oer-updates/2021/fy21-ffo-schedule.html)