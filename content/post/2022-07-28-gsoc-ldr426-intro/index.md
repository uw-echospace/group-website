---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Hello from Dingrui Lei, GSoC contributor of Echoshader!"
date: 2022-07-28T00:00:00-08:00
authors: 
  - Dingrui Lei
  - landungs
slug: 
draft: false
tags: 
summary: "Echospace hosted a Google Summer of Code (GSoC) contributor to jump start [echoshader](https://github.com/OSOceanAcoustics/echoshader), a new package for interactive visualization of echosounder data."

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

_Echospace collaborates with the [Integrated Ocean Observing Systems (IOOS)](https://ioos.us/) in the [Google Summer of Code (GSoC)](https://summerofcode.withgoogle.com/) program in 2022 to jump start an echosounder data interactive visualization package called [echoshader](https://github.com/OSOceanAcoustics/echoshader)._

_[Dingrui Lei](https://github.com/ldr426) is our great GSoC contributor, and our very own [Don Setiawan](author/don-setiawan) is the primary mentor._

-------------------------------

My name is Dingrui Lei and I am a new graduate student at Rice University. My experience has given me a broader understanding of how computer science knowledge can solve engineering problems and facilitate new tech development. I’d like to utilize my computer science knowledge to solve engineering problems.

Before contacting the [IOOS](https://ioos.us/) community, I read the article "[Understanding Our Ocean with Water-Column Sonar Data](https://storymaps.arcgis.com/stories/e245977def474bdba60952f30576908f)," and an introduction to the project [echopype](https://uw-echospace.github.io/software/echopype/). Sonar is very intriguing to me, it can continuously detect the activities of sea creatures in the dimension of space and time. The depth of fish clusters changing with solar radiation really made me see the splendid usefulness of sonar data.

![The IOOS Logo - The U.S. Integrated Ocean Observing System (IOOS)](https://ioos.us/images/IOOS_Emblem_Tertiary_B_RGB.png)

One of the main focuses of the [Echospace](https://uw-echospace.github.io/author/echospace/) team is sampling and interpretation of ocean acoustic data. [Echopype](https://github.com/OSOceanAcoustics/echopype) sits in the middle, extracts raw data from the cloud or file server, converts them to netCDF or Zarr, and performs denoising and calibration. Another job is to interpret, where I give my effort to build a library called echoshader that can help oceanographers discover certain patterns from it. [Echoshader](https://github.com/OSOceanAcoustics/echoshader), an open source project, aims to enhance the ability to interactively visualize large amounts of cloud-based data to accelerate the data exploration and discovery process. Ocean sonar data are generated from echopype, which handles the normalization, preprocessing and organization of echo data. Echoshader will be developed in parallel with the ongoing development of echopype. 

As a participant of GSoC, I am developing the main APIs of echoshader based on the [HoloViz](https://holoviz.org/) suite of tools, test configuration for using echoshader widgets in Panel dashboards, and create Jupyter notebooks to demo use of the combination of tools. 

![Deploying Panel (Holoviz) dashboards using Heroku Container Registry | by  Ali Shahid | Towards Data Science](https://miro.medium.com/max/1400/1*xQEm58a7c_g1Go9G5NMyuw.jpeg)

Before starting coding, I read lots of documents to find the most suitable tool. Although there are many excellent and fantastic visualizing libraries with Python, such as plotly and bokh, they can not process xarray directly, which is a kind of multidimensional labeled data massively used in echopype.  Then I locked my eyes on HoloViz ecosystem, whose tools and examples generally work with any Python standard data types (lists, dictionaries, etc.), plus Pandas or Dask DataFrames and NumPy, Xarray, or Dask arrays.
After determining which type of tool to use, I began to read a user guide about HoloViz libraries. There are several libraries mainly used in echoshader: hvplot, Holoviews, GeoViews and Panel.  Hvplot and HoloViews declare objects for instantly visualizable data, building Bokeh plots from convenient high-level specifications. GeoViews visualize geographic data corresponding to ship survey datasets. Panel assembles grams and control widgets from these different libraries into a layout which could be displayed in a Jupyter notebook and in a standalone servable dashboard.  In addition to HoloViz libraries, PyVista and other libraries are involved for 3D extension, which also fit well in panel layout. Also, benchmarking and doc work are required for each module.
Below are some screenshots of the different visualization functionalities I am developing:

![2d_echogram](https://user-images.githubusercontent.com/15334215/186999651-76081a29-11f8-4d37-b3a9-fca0ad49a03c.png)

![tracks](https://user-images.githubusercontent.com/15334215/186999662-ba744a49-b02e-4451-a716-f8c8df654053.png)

![curtain](https://user-images.githubusercontent.com/15334215/186999678-2bf77985-aab3-42f8-88f9-1f2c78d3b2eb.png)

Although the project is not difficult, there are some other challenges I face. Learning Git and Github is a prerequisite for me to participate in open source projects for the first time. It is also my first time to collaborate with an English-speaking team. I had difficulty reading and writing English documents, not to mention, communicating. Fortunately, the mentors, Wu-jung, Don, Valentina, Brandon and Emilio are all kind and warmhearted, willing to give me suggestions and guidance.

I really recommend future GSoC participants select the IOOS organization and echospace team as your target and exploit your ability and talent to contribute to the community.  Water is extremely significant for holding an adequate food supply and a productive environment for all living organisms. So working here can not just improve your coding and teamwork capability, but also create a beautiful tomorrow for ourselves and our Mother Earth. 
