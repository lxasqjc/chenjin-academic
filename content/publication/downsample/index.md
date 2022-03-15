---
title: Learning to Downsample for Segmentation of Ultra-High Resolution Images
publication_types:
  - "1"
authors:
  - Chen Jin
  - Ryutaro
  - Thomy Mertzanidou
  - Eleftheria Panagiotaki
  - Daniel C. Alexander
publication: ICLR, 2022
publication_short: ICLR, 2022
abstract: Segmentation of ultra-high resolution images with deep learning is challenging because of their enormous size, often millions or even billions of pixels. Typical solutions drastically downsample the image uniformly to meet memory constraints, implicitly assuming all pixels equally important by sampling at the same density at all spatial locations. However this assumption is not true and compromises the performance of deep learning techniques that have proved powerful on standard-sized images. For example with uniform downsampling, see green boxed region in Fig. 1, the rider and bike do not have enough corresponding samples while the trees and buildings are oversampled, and lead to a negative effect on the segmentation prediction from the low-resolution downsampled image. In this work we show that learning the spatially varying downsampling strategy jointly with segmentation offers advantages in segmenting large images with limited computational budget. Fig. 1 shows that our method adapts the sampling density over different locations so that more samples are collected from the small important regions and less from the others, which in turn leads to better segmentation accuracy. We show on two public and one local high-resolution datasets that our method consistently learns sampling locations preserving more information and boosting segmentation accuracy over baseline methods.
draft: false
share: true
slides: ""

summary: We introduce an approach for learning to downscale high-resolution images for segmentation tasks. The main motivation is to adapt the sampling budget to the difficulty of segmented pixels/regions. We show that learning the spatially varying downsampling strategy jointly with segmentation offers advantages in segmenting large images with a limited computational budget.

links:
  - name: Page
    url: https://lxasqjc.github.io/learn-downsample.github.io/
url_video: https://recorder-v3.slideslive.com/?share=63834&s=2a9de36c-8627-40cd-9fa5-ef8accc61cca
url_pdf: https://openreview.net/pdf?id=lobjb6Qw0p
url_code: https://github.com/lxasqjc/Deformation-Segmentation
doi: ""
featured: true
tags:
  - ""
projects:
  - downsample
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2022-01-28T00:40:17.187Z
publishDate: 2022-01-28T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
