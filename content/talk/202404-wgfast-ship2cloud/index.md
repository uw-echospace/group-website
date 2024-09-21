---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A ship-to-cloud machine learning pipeline built on the open-source Python Echostack software tools"
event: WGFAST 2024 Meeting
event_url: https://www-iuem.univ-brest.fr/wgfast/?lang=en
location: Brest, France
address:
  street:
  city:
  region:
  postcode:
  country: 
summary: 
abstract: "Successful application of machine learning (ML) methodology requires iterative development and testing of not only the models but also the entire workflow on the very platform and operating scenario the development aims to serve, before the framework is generalized to other settings. In this work we present our implementation of a ship-to-cloud ML pipeline during the 2023 Pacific hake acoustics-trawl survey. Hake is a keystone species in the northern California Current ecosystem and supports the largest fishery on the west coast of the U.S. By integrating an echogram semantic segmentation model targeting hake with the “Echostack” suite of open-source Python software packages, our pipeline transformed raw instrument-generated binary files into hake aggregation predictions, which were displayed in two ways: in a configurable Python dashboard that allows sharing widely with collaborators, and in Echoview for aligning with live screening. We transmitted data products with reduced resolution and the corresponding ML predictions to the cloud in sub-realtime, allowing shore-side interaction. We plan to incorporate biomass estimation based on initial fish biometric measurements, automate the orchestration of this ship-to-cloud pipeline, and prototype an ML-driven annotation framework in the future."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-04-11T09:00:00-05:00
# date_end: 2020-10-29T16:30:00-05:00
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - leewj
  - vms16
  - ldr426
  - zhmiao
tags:
  - open-source
  - pipeline
  - fisheries acoustics
  - scientific computing
  - data standard
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
projects: []
---
