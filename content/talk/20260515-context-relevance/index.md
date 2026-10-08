---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploring context relevance for echogram classification tasks using class activation map methods."
event: 190th Meeting of the Acoustical Society of America
event_url: https://acousticalsociety.org/philadelphia/
location: Philadelphia, PA, United States
address:
  street:
  city:
  region:
  postcode:
  country: 
summary: 
abstract: "Echograms are images commonly used to visualize and classify scattering sources in water column sonar data. We developed a convolutional neural network-based binary semantic segmentation model that classifies regions of echogram as either Pacific hake, a trophically important semi-pelagicgroundfish, or background. Interpretation of the model’s reasoning in making decisions was difficult for two reasons. First, the model setup does not account for variability within human-annotated hake aggregations, which include identifiable subtypes. Second, heterogeneous echogram context, including unlabeled non-hake biological aggregations and bathymetry features, exists in the background. To better understand if and how echogram context influences the model behavior across different hake aggregation subtypes and environments, we explored class activation map (CAM) methods, which highlight regions that most influence a model’s decisions. Traditionally, CAM methods identify which parts within an object a model uses to predict its class. While this within-object viewpoint is useful, our analysis using gradient-based and eigendecomposition CAMs suggested that the model also utilizes echogram features outside specific objects, or the “context” in making decisions. We will conclude by discussing how CAM analysis may be used as a tool to design or select model architectures that promote desired model behaviors."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2026-05-15T10:00:00-05:00
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2020-10-10T08:28:33-08:00

authors:
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
