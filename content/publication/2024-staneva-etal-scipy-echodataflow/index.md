---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Echodataflow: Recipe-based Fisheries Acoustics Workflow Orchestration"
authors: ["V Staneva", "S Butala", "L Setiawan", "W-J Lee"]
date: 2024-07-10
doi: "https://doi.org/10.25080/JXDK4427"

# Customize
share: false
markup: md
math: true


# Schedule page publish date (NOT publication's date).
publishDate: 2024-07-10

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 23rd Python in Science Conference"
publication_short: "SciPy Proceedings"

abstract: "With the influx of large data from multiple instruments and experiments, scientists are wrangling complex data pipelines that are context-dependent and non-reproducible. We demonstrate how we leverage Prefect ([Prefect](https://www.prefect.io/), 2024), a modern orchestration framework, to facilitate fisheries acoustics data processing. We built a Python package Echodataflow ([Echodataflow](https://github.com/OSOceanAcoustics/echodataflow), 2024) which 1) allows users to specify workflows and their parameters through editing text “recipes” which provide transparency and reproducibility of the pipelines; 2) supports scaling of the workflows while abstracting the computational infrastructure; 3) provides monitoring and logging of the workflow progress. Under the hood, Echodataflow uses Prefect to execute the workflows while providing a domain-friendly interface to facilitate diverse fisheries acoustics use cases. We demonstrate the features through a typical ship survey data processing pipeline."

# Summary. An optional shortened abstract.
summary: " "

tags:
  - open-source
  - fisheries acoustics
  - scientific computing
  - community engagement
categories: ["sonar"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  caption: ""
  Placement options: 1
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
