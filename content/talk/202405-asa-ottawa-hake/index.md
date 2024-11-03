---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Variability and influence of fisheries acoustic echogram annotations on machine learning applications"
event: ASA 2024 spring meeting (ASA - The Acoustical Society of America)
event_url:
location: Ottawa, ON, Canada
address:
  street:
  city:
  region:
  postcode:
  country: 
summary: 
abstract: "High-frequency echosounders are the workhorse in fisheries and marine ecological surveys. Due to the inherent complexity of biological aggregations and ambiguity in interpreting echoes from species of similar size and anatomical compositions, echogram annotation typically requires combining spectral information referencing scattering physics, biological ground-truth from nearby net-trawls, and empirical school morphology of specific fish species. Here, we investigate the variability of echogram annotations and its influence on machine learning applications using data from the biennial Pacific hake acoustic-trawl survey. Compared to many other fish species, hake tend to possess less defined school boundaries with variable acoustic features and often form mixed-species aggregations in the mesopelagic. Nonnegative matrix factorization and hierarchical clustering of volume backscattering strength (Sv) distributions across the 18, 38, and 120 kHz channels revealed a spectrum of annotation region types that reflect differences in morphological and acoustic features as well as differences in annotator style. This variability likely contributes to the observed variable segmentation behavior of deep learning models trained using this dataset. These results highlight the importance of considering the diversity of echogram annotation, its connection to scattering physics and the underlying aggregation composition, and the incorporation of such information in developing machine learning models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-05-13
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
  - leewj
  - vms16
  - ctuguina
tags:
  - fisheries acoustics
  - machine learning

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
links:
- name: DOI
  url: https://doi.org/10.1121/10.0026900
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
