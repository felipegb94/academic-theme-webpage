---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Charm SPH"
summary: "Distributed-memory SPH simulation with Charm++"
abstract: "Smoothed particle hydrodynamics (SPH) is a method for simulating the dynamics of fluids. In this project, we implement a distributed memory SPH simulation engine with the Charm++ asynchronous message passing parallel programming framework. We employ a hybrid decomposition strategy that targets the parallelization of both the physical domain and force computation. This strategy allowed us to take advantage of the three core components of the Charm++ paradigm; object migratability, overdecomposition, and message-drive execution. We evaluate the strong scaling of our implementation up to 504 cores (8 nodes) and find it scales linearly.

This work was presented at ASME IDETC Conference, 2016 and the Blue Water Symposium, 2016"
authors: []
tags: ["research"]
categories: []
date: 2016-06-01

# Optional external URL for project (replaces project detail page).
external_link: ""

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

url_code: "https://github.com/uwsbel/CharmSPH"
url_pdf: ""
url_slides: "files/slides-2016-asme.pdf"
url_poster: "files/poster-2016-bwsymposium.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
