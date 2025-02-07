---
title: "iToF2dToF: A Robust and Flexible Representation for Data-driven Time-of-Flight Imaging"
date: 2021-01-01
publishDate: 2021-01-01
authors: ["Felipe Gutierrez-Barragan", "Huaijin Chen", "Mohit Gupta", "Andreas Velten", "Jinwei Gu"]
publication_types: ["3"]
abstract: "Indirect Time-of-Flight (iToF) cameras are a promising depth sensing
technology. However, they are prone to errors caused by multi-path interference
(MPI) and low signal-to-noise ratio (SNR). Traditional methods, after
denoising, mitigate MPI by estimating a transient image that encodes depths.
Recently, data-driven methods that jointly denoise and mitigate MPI have become
state-of-the-art without using the intermediate transient representation. In
this paper, we propose to revisit the transient representation. Using
data-driven priors, we interpolate/extrapolate iToF frequencies and use them to
estimate the transient image. Given direct ToF (dToF) sensors capture transient
images, we name our method iToF2dToF. The transient representation is flexible.
It can be integrated with different rule-based depth sensing algorithms that
are robust to low SNR and can deal with ambiguous scenarios that arise in
practice (e.g., specular MPI, optical cross-talk). We demonstrate the benefits
of iToF2dToF over previous methods in real depth sensing scenarios."
featured: true
publication: "*IEEE Transactions on Computational Imaging*"
# url_code: "https://github.com/felipegb94/ToFSim"
url_pdf: "https://ieeexplore.ieee.org/document/9609533"
url_arxiv: "https://arxiv.org/abs/2103.07087"
url_video: "https://youtu.be/tEMinzXNTv8"
url_project: "/~felipe/project-pages/2021-itof2dtof/"
summary: "Proposed to train data-driven ToF models to estimate an intermediate representation that encodes depths, instead of depthmaps."

---

