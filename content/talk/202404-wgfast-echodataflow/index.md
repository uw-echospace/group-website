---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scalable and configurable echosounder data workflows"
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
abstract: "Acoustic fisheries surveys and ocean observing systems collect terabytes of echosounder data that require custom processing pipelines to obtain biological estimates of target species, which often can be hard to reuse or adapt. There is a rising need to scale computations on local and cloud computing clusters. However, this requires an elaborate configuration of computing infrastructure and distributed computing libraries, and the ability to monitor progress and performance.

In this talk, we describe how we address some of these challenges by developing a framework that allows researchers to execute complex echosounder data processing procedures on both local and cloud platforms by editing text-based configuration “recipe” templates. We create a user-friendly Python package Echodataflow that leverages Prefect, a modern workflow orchestration framework, to run large data pipelines (reading raw files, computing volume backscatter, performing frequency differencing, etc.) with only a few lines of code. We will demonstrate how we used Echodataflow to process ship data from the U.S.-Canada Pacific Hake Acoustic Trawl Survey and discuss other use cases. We believe that this approach will increase the reproducibility and transparency of fisheries acoustics data pipelines and allow the community to learn from each other’s work.
" 
# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-04-11T09:00:00-05:00
# date_end: 2020-10-29T16:30:00-05:00
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - vms16
  - sbutala
  - leewj
  - landungs
tags:
  - open-source
  - pipeline
  - fisheries acoustics
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
