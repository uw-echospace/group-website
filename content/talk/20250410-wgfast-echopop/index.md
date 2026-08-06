---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Echopop: An open-source software package for acoustics-based population estimates and biological inversion."
event: WGFAST 2025
event_url: https://wgfast.hafro.is/
location: Hafnarfjörður, Iceland
address:
  street:
  city:
  region:
  postcode:
  country: 
summary: 
abstract: "Acoustic-trawl surveys provide estimates of biological distributions that can inform stock assessments and other ecosystem-based management strategies. These measurements can also derive other biometrics (e.g. average body length) and behavioral information (e.g. tilt distributions) via inversion that can supplement sparse biological datasets. Acoustic and biological data processing methods often differ significantly across research groups and require bespoke code that could hinder collaborative efforts. As part of the effort to enhance the data processing workflow for the Pacific hake survey, we have developed Echopop (https://github.com/OSOceanAcoustics/echopop), a Python software package for integrating acoustic and biological trawl data to estimate biomass and other biological quantities. Echopop allows configuration through text-based “recipes” and is accompanied by detailed documentation and interactive Juptyer notebook usage examples. At present, it supports reproducing historical biomass estimates of Pacific hake, inverting for abundance of euphausiids, and ingesting biological trawl data during surveys in near real-time. In the next stage of development, we will expand the package to support a broader range of input data formats, scattering models, and inversion methods, along with enhanced interoperability across other packages within the Echostack software suite."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2025-04-10T16:20:00-16:40
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - bmlucca
  - leewj
  - Rebecca Thomas
  - Alicia Billings
  - Elizabeth Phillips
  - Julia Clemons
tags:
  - open-source
  - fisheries acoustics
  - scientific computing
  - community engagement

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video: 

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["echopop"]
---
