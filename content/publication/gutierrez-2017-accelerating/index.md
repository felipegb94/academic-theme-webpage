---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accelerating permutation testing in voxel-wise analysis through subspace tracking: A new plugin for SnPM"
authors: [Felipe Gutierrez-Barragan, Vamsi K. Ithapu, Chris Hinrichs,Camille Maumet, Sterling C Johnson, Thomas E Nichols,Vikas Singh, Alzheimer's Disease Neuroimaging Initiative]
date: 2017-01-01
doi: ""



# Schedule page publish date (NOT publication's date).
publishDate: 2017-01-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*NeuroImage*"
publication_short: ""

abstract: "Permutation testing is a non-parametric method for obtaining the max null distribution used to compute corrected p-values that provide strong control of false positives. In neuroimaging, however, the computational burden of running such an algorithm can be significant. We find that by viewing the permutation testing procedure as the construction of a very large permutation testing matrix, , one can exploit structural properties derived from the data and the test statistics to reduce the runtime under certain conditions. In particular, we see that  is low-rank plus a low-variance residual. This makes  a good candidate for low-rank matrix completion, where only a very small number of entries of  ( of all entries in our experiments) have to be computed to obtain a good estimate. Based on this observation, we present RapidPT, an algorithm that efficiently recovers the max null distribution commonly obtained through regular permutation testing in voxel-wise analysis. We present an extensive validation on a synthetic dataset and four varying sized datasets against two baselines: Statistical NonParametric Mapping (SnPM13) and a standard permutation testing implementation (referred as NaivePT). We find that RapidPT achieves its best runtime performance on medium sized datasets (), with speedups of 1.5× - 38× (vs. SnPM13) and 20x-1000× (vs. NaivePT). For larger datasets () RapidPT outperforms NaivePT (6× - 200×) on all datasets, and provides large speedups over SnPM13 when more than 10000 permutations (2× - 15×) are needed. The implementation is a standalone toolbox and also integrated within SnPM13, able to leverage multi-core architectures when available."

# Summary. An optional shortened abstract.
summary: "Proposed an algorithm that speeds up permutation testing in neuroimaging data by exploting structural properties of the test statistics derived from the data. The implementation is available in a [development version](https://github.com/felipegb94/SnPM-devel) of the widely used neuroimaging toolbox, SnPM."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1703.01506
url_code: https://github.com/felipegb94/RapidPT
url_dataset:
url_poster:
url_project: http://felipegb94.github.io/RapidPT/
url_slides:
url_source: https://www.sciencedirect.com/science/article/abs/pii/S1053811917305931?via%3Dihub
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: ""
  focal_point: ""
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
