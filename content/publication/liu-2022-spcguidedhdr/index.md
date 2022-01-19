---
title: "Single-Photon Camera Guided Extreme Dynamic Range Imaging"
date: 2022-01-01
publishDate: 2022-01-01
authors: ["Yuhao Liu", "Felipe Gutierrez-Barragan", "Atul Ingle", "Mohit Gupta", "Andreas Velten"]
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
publication: "IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)"
url_code: "https://github.com/Way-Yuhao/Single-Photon-Guided-HDR"
url_pdf: "https://openaccess.thecvf.com/content/WACV2022/html/Liu_Single-Photon_Camera_Guided_Extreme_Dynamic_Range_Imaging_WACV_2022_paper.html"
url_video: "https://www.youtube.com/watch?v=i_mzoXlxshs"
url_project: "https://www.yuhaoliu.net/spc-guided-hdr"
summary: "Proposed to train data-driven ToF models to estimate an intermediate representation that encodes depths, instead of depthmaps."

---

