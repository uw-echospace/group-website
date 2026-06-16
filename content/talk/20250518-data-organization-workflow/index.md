---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An open-source workflow for organizing fisheries acoustics data from transect surveys for machine learning applications."
event: 188th Meeting of the Acoustical Society of America joint with 25th International Congress on Acoustics
event_url: https://acousticalsociety.org/new-orleans-2025/
location: New Orleans, LA, United States
address:
  street:
  city:
  region:
  postcode:
  country: 
summary: 
abstract: "As the volume of active water column sonar data expands, automated, machine learning (ML)-based echogram analysis methods are increasingly used to detect biological scatterers at scale. Semantic segmentation, which labels each pixel in an image, is a class of methods that is increasingly adopted to detect and classify acoustic targets. However, survey echograms are not standard images: they have spatiotemporal associations and originate from data collection strategies targeting potentially patchy biological aggregations. In the context of transect surveys, we consider four key requirements to create echogram datasets for ML applications: (1) how to partition data based on survey information, (2) how to subsample spatially via transect-based groupings to minimize model overfit, (3) how to create region masks of biological scatterers to exclude noise and other contaminating sources (e.g., seafloor), and (4) how to reconcile different spatiotemporal resolutions of echo data and human annotations. We present a generalizable workflow for constructing echogram datasets that addresses these requirements, and discuss our implementation using two open-source tools, Echopype and Echoregions. We highlight how the workflow enables a flow of echo data with ancillary spatiotemporal information propagating downstream, and demonstrate its scalability in organizing a multi-year dataset from a fisheries acoustic-trawl survey."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2025-05-18
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - ctuguina
tags:
  - fisheries acoustics
  - machine learning
  - scientific computing
  - open-source

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
projects: []
---
