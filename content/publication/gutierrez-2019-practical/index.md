---
title: "Practical Coding Function Design for Time-of-Flight Imaging"
date: 2019-01-01
publishDate: 2020-03-30T01:13:34.514024Z
authors: ["Felipe Gutierrez-Barragan", "Syed Azer Reza", "Andreas Velten", "Mohit Gupta"]
publication_types: ["1"]
abstract: "The depth resolution of a continuous-wave time-of-flight (CW-ToF) imaging system is determined by its coding functions. Recently, there has been growing interest in the design of new high-performance CW-ToF coding functions. However, these functions are typically designed in a hardware agnostic manner, ie, without considering the practical device limitations, such as bandwidth, source power, digital (binary) function generation. Therefore, despite theoretical improvements, practical implementation of these functions remains a challenge. We present a constrained optimization approach for designing practical coding functions that adhere to hardware constraints. The optimization problem is non-convex with a large search space and no known globally optimal solutions. To make the problem tractable, we design an iterative, alternating least-squares algorithm, along with convex relaxation of the constraints. Using this approach, we design high-performance coding functions that can be implemented on existing hardware with minimal modifications. We demonstrate the performance benefits of the resulting functions via extensive simulations and a hardware prototype."
featured: true
publication: "*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition*"
url_code: "https://github.com/felipegb94/ToFSim"
url_pdf: "http://openaccess.thecvf.com/content_CVPR_2019/html/Gutierrez-Barragan_Practical_Coding_Function_Design_for_Time-Of-Flight_Imaging_CVPR_2019_paper.html"
url_video: "https://www.youtube.com/watch?v=tzs2WuwZ4ag"
url_project: "/~felipe/project-pages/2019CVPRPracticalToFCodes/"
# url: "customHTML/2019CVPRPracticalToFCodes/"
summary: "Proposed a new set of ToF coding schemes that achieve higher depth precision than traditional codes while adhering to practical hardware constraints."
---

