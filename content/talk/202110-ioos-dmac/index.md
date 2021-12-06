---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scalable, interoperable processing of water column sonar data for biological applications using the echopype Python package"
event: IOOS DMAC Tech Webinar
event_url:
location: Online
address:
  street:
  city:
  region:
  postcode:
  country: USA
summary: " "
abstract: High-frequency sonar systems deployed on a growing variety of ocean observing platforms are creating an increasing deluge of water column sonar data. These echosounder and ADCP systems are widely used in fisheries and marine ecological studies. Efficient and integrated analysis of these data, either across different sonar instruments or with other types of ocean data, holds a distinct potential for monitoring and understanding the response of marine organisms to the rapidly changing environment and to study marine ecosystems at broad spatial and temporal scales. We will briefly discuss the current state of water column sonar data, then present and demonstrate echopype (https://github.com/OSOceanAcoustics/echopype), an open-source Python software package designed to address these needs. Echopype standardizes water column sonar data from diverse instrument vendor formats into a variant of the SONAR-netCDF4 community convention optimized for usability and analysis, providing instrument-agnostic, netCDF-based exploration and use of sonar data. By leveraging existing open-source Python libraries optimized for distributed computing (xarray, dask, zarr, fsspec), it enables computational interoperability and scalability in both local and cloud computing environments. We will also demonstrate echopype's data processing capabilities, entice your contributions to the package, and briefly touch on our ongoing echopype-enabled work developing cloud-native data processing workflows and machine learning applications.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-10-28T15:00:00-05:00
# date_end: 2020-10-29T16:30:00-05:00
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - emiliom
  - leewj
tags:
  - open-source
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
url_video: https://mmancusa.webex.com/mmancusa/ldr.php?RCID=ef5826f5581e1751950394fc8a54e579

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
