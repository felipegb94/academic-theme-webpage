---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ToF Codes and MPI"
summary: "Performance of ToF coding functions under global illumination"
abstract: "For my final project for the Computational Imaging course (ECE901) I evaluated the performance of different continuous-wave time-of-flight coding functions under the presence of global illumination (direct + multi-bounce illumination). I compare the performance of the coding functions proposed [here](http://wisionlab.cs.wisc.edu/project/tofcoding/) with regular sinusoid coding. They are evaluated on a complex scene with a strong global illumination component. To obtain ToF brightness measurements, I obtain the impulse response for each scene pixel using a [transient rendering code](http://giga.cps.unizar.es/~ajarabo/pubs/transientSIGA14/), then convolve the response with the coding function, and then integrate. "
authors: []
tags: ["course"]
categories: []
date: 2018-06-01

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

url_code: ""
url_pdf: "files/report-2018-multipathtof.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
