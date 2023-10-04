---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "A summer of Refactoring Echoshader!"
date: 2023-09-18T00:00:00-08:00
authors:
  - Dingrui Lei
slug:
draft: false
tags:
summary: "Echospace hosted a contributor - Dingrui Lei, to refactor echoshader - a package for interactive visualization of echosounder data."  

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

_Echospace recruited contributor Dingrui Lei in 2023 to refactor an echosounder data interactive visualization package called [echoshader](https://github.com/OSOceanAcoustics/echoshader)._

_[Dingrui Lei](https://github.com/ldr426) is our contributor._

-------------------------------
# My 2023 Summer Internship with Echoshader: A Dive into Advanced Ocean Sonar Data Visualization
Author: [Dingrui Lei](mailto:leidingrui426@gmail.com)

Ref 1: [Slides](https://docs.google.com/presentation/d/1HmL2-luVmA9T5HfS3L1kBu8c7dDHo75znwaS-8YlTSE/edit#slide=id.p) of presentation 

Ref 2: [Docs](https://echoshader--140.org.readthedocs.build/en/140/intro.html)  for this version

Hello, readers! I'm excited to share my summer internship experience working on the fascinating project, Echoshader. This Python package, designed to enhance the visualization of ocean sonar data, has been my focus this summer. While I won't be delving into technical jargon, I'll give you a glimpse of my journey, the challenges I faced, and the accomplishments achieved during my internship. The prototype was built during [GSoC 2022](https://summerofcode.withgoogle.com/programs/2022/organizations/ioos).

## Echoshader: Bridging the Gap in Ocean Sonar Data Visualization

Before I jump into the technical details, let's take a moment to understand the significance of ocean sonar systems. These systems, including echosounders, are the unsung heroes of marine research. They help scientists study marine life by emitting sound waves and analyzing the echoes they bounce back. Think of it as an underwater ultrasound for the ocean. The data generated from these systems is invaluable for monitoring and conserving our marine ecosystems.

Echoshader, our summer project, aims to make this data more accessible and interactive. It's like a powerful toolset that enables scientists and researchers to visualize and analyze ocean sonar data effortlessly. But let's get into the nitty-gritty of my experience.

## Building the Echoshader: A Structured Journey

My summer project was all about creating and refining the Echoshader package. This package is the backbone of our mission, providing oceanographers and researchers with the tools they need to visualize and understand ocean sonar data. Here's how I structured my work:

### 1. The Echoshader Class: A Controller for Visualization

At the heart of Echoshader lies the Echoshader class. This class is like the conductor of an orchestra, coordinating user interactions, data updates, and visualizations. My task was to make sure this class was robust and user-friendly.

I defined the class and set up initial values and interactive widgets. These widgets allow users to tweak parameters and explore data interactively.

### 2. Callbacks and Streams: Making It Interactive

Echoshader needed to be interactive, allowing users to explore data dynamically. This required creating callback methods and stream objects. These elements connected user interactions to visualization updates, making the whole experience smooth and intuitive.
<img width="594" alt="image" src="https://github.com/ldr426/add-ldr426-page/assets/56751303/472ca1bf-4ec3-4e27-82db-20dba3f7fa58">

### 3. Extending `Xarray` with Accessors: A New Level of Functionality

One of the exciting challenges I encountered was extending `xarray`'s functionality using accessors. This means adding custom methods and functionality to `xarray` objects, without cluttering the code with custom functions. We created a custom "eshader" accessor, which allowed us to take echogram visualization to the next level.

## A Glimpse into Echogram Visualization

Echogram visualization is where the magic happens. It's not just about pretty pictures; it's about gaining insights into marine life and ecosystems.

-   **Echograms for Identifying Fish**: Fisheries scientists rely on echograms to identify fish aggregations, scrolling through data collected on ships to assess populations.
-   **Echograms for Observing Zooplankton**: Oceanographers use echograms to observe zooplankton movements in mooring data over extended periods.
-   **Tricolor Echograms**: The "tricolor" echogram helps distinguish different fish species, thanks to its clever mapping of three frequencies to RGB colors.
<img width="613" alt="image" src="https://github.com/ldr426/add-ldr426-page/assets/56751303/57472c8e-eef9-432a-83dd-2292b4eea546">

## Tracking and Curtain Visualization

One of the most exciting aspects of Echoshader is tracking and curtain visualization. It's like having a GPS for underwater data.

-   **Echogram-Control Mode**: Visualizing data on a map helps assess fish associations with environmental variables.
-   **Track-Control Mode**: Highlighting ship track sections on the map while viewing corresponding echograms offers precise insights into marine life at specific locations.
-   **Curtain Visualization**: Representing longer data sections as curtains provides a broader spatial perspective on fish aggregations.
<img width="609" alt="image" src="https://github.com/ldr426/add-ldr426-page/assets/56751303/dab25ce8-bba3-4062-85e9-4ce3231172fc">

<img width="502" alt="image" src="https://github.com/ldr426/add-ldr426-page/assets/56751303/2a1a33df-c639-4b53-9df2-ae2523cd3901">

## Histograms and Statistics Tables: Tools for Deeper Analysis

Histograms and statistics tables are essential for fisheries scientists.

-   **Focused Analysis**: Scientists can zoom in on specific data sections to examine volume backscattering strength (Sv) distribution and understand the types of fish present.
-   **Multi-Channel Comparisons**: Comparing Sv distributions across multiple echosounder channels helps determine fish aggregation composition, offering valuable insights into the ecosystem.
<img width="722" alt="image" src="https://github.com/ldr426/add-ldr426-page/assets/56751303/623ca032-cab8-4fe0-8f37-57774a64e1b0">

## In Conclusion: An Incredible Summer Journey

My summer internship with Echoshader has been a remarkable journey. I've had the privilege of contributing to a project to advance oceanographic research and fisheries science. Echoshader isn't just a package; it's a gateway to uncovering the secrets of our oceans.

If you're curious about ocean sonar data or want to explore the world of marine life, Echoshader is your partner in discovery. Feel free to reach out if you have questions or want to join us on this exciting journey. Until next time, happy exploring!
