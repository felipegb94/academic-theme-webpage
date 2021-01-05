---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning ToF Depth Estimation"
abstract: "For the Deep Neural Networks course, my teammates and I explored to the idea of training a neural network to learn to predict depth from continuous-wave time-of-flight (ToF) data. Depth inference from ToF measurements can be done with an analytical formula. This formula, however, makes some simplifying assumptions on the data and does not use the fact that neighbor pixels should have similar depth. We developed a training dataset of simulated ToF data for various shapes and trained a fully convolutional network to perform depth inference."
summary: "Depth Inference from ToF data with Neural Networks"
authors: []
tags: ["course"]
categories: []
date: 2017-01-01

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

url_code: "https://github.com/felipegb94/NeuralWaveToF"
url_pdf: "/files/report-2017-neuralwavetof.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

For the Deep Neural Networks course, my teammates and I explored to the idea of training a neural network to learn to predict depth from continuous-wave time-of-flight (ToF) data. Depth inference from ToF measurements can be done with an analytical formula. This formula, however, makes some simplifying assumptions on the data and does not use the fact that neighbor pixels should have similar depth. We developed a training dataset of simulated ToF data for various shapes and trained a fully convolutional network to perform depth inference.