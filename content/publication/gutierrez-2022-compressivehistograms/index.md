---
title: "Compressive Single-Photon 3D Cameras"
date: 2022-06-07
publishDate: 2022-06-07
authors: ["Felipe Gutierrez-Barragan", "Atul Ingle", "Trevor Seets", "Mohit Gupta", "Andreas Velten"]
publication_types: ["1"]
abstract: "Single-photon avalanche diodes (SPADs) are an emerging pixel technology for time-of-flight (ToF) 3D cameras that can capture the time-of-arrival of individual photons at picosecond resolution. To estimate depths, current SPAD-based 3D cameras measure the round-trip time of a laser pulse by building a per-pixel histogram of photon timestamps. As the spatial and timestamp resolution of SPAD-based cameras increase, their output data rates far exceed the capacity of existing data transfer technologies. One major reason for SPAD's bandwidth-intensive operation is the tight coupling that exists between depth resolution and histogram resolution. To weaken this coupling, we propose compressive single-photon histograms (CSPH). CSPHs are a per-pixel compressive representation of the high-resolution histogram, that is built on-the-fly, as each photon is detected. They are based on a family of linear coding schemes that can be expressed as a simple matrix operation. We design different CSPH coding schemes for 3D imaging and evaluate them under different signal and background levels, laser waveforms, and illumination setups. Our results show that a well-designed CSPH can consistently reduce data rates by 1-2 orders of magnitude without compromising depth precision."
featured: true
# publication: "*IEEE Transactions on Computational Imaging*"
publication: "*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition*"
url_code: "https://github.com/felipegb94/compressive-spad-lidar-cvpr22"
url_pdf: "https://pages.cs.wisc.edu/~felipe/project-pages/2022-compressive-histograms/assets/2022cvpr_csph_v5_with_supplement_v6.pdf"
url_video: "https://youtu.be/RDJYQkmqES0"
url_project: "/~felipe/project-pages/2022-compressive-histograms/"
summary: "An online compression framework for SPAD-based 3D cameras based on the coded projections of photon timestamp data."

---

