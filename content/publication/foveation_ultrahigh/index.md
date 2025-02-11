---
title: Foveation for Segmentation of Ultra-High Resolution Images
publication_types:
  - "3"
authors:
  - Chen Jin
  - Ryutaro Tanno
  - Moucheng Xu
  - Thomy Mertzanidou
  - Daniel C. Alexander
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *arXiv, 2020*
publication_short: arXiv, 2020
abstract: Segmenting histology images is challenging because of the sheer size of the images with millions or even billions of pixels. Typical solutions include dividing input images into patches of fixed size and/or down-sampling to meet memory constraints. Such operations incur information loss in the field-of-view (FoV) i.e., spatial coverage and the image resolution. The impact on segmentation performance is, however, as yet understudied. In this work, we start with a motivational experiment which demonstrates that the trade-off between FoV and resolution affects the segmentation performance on ultra-high resolution images—and furthermore, its influence also varies spatially according to the local patterns in different areas. We then introduce foveation module, a learnable “dataloader” which, for a given ultra-high resolution image, adaptively chooses the appropriate configuration (FoV/resolution trade-off) of the input patch to feed to the downstream segmentation model at each spatial location of the image. The foveation module is jointly trained with the segmentation network to maximise the task performance. We demonstrate on three publicly available high-resolution image datasets that the foveation module consistently improves segmentation performance over the cases trained with patches of fixed FoV/resolution trade-off. Our approach achieves the SoTA performance on the DeepGlobe aerial image dataset. On the Gleason2019 histopathology dataset, our model achieves better segmentation accuracy for the two most clinically important and ambiguous classes (Gleason Grade 3 and 4) than the top performers in the challenge by 13.1% and 7.5%, and improves on the average performance of 6 human experts by 6.5% and 7.5%. Our code and trained models are available at [https://github.com/lxasqjc/Foveation-Segmentation](https://github.com/lxasqjc/Foveation-Segmentation).
draft: false
share: true
slides: ""

summary: On top of [prior foveation work at MICCAI 2020](https://chenjin.netlify.app/publication/foveation/), in this extended version, we further introduce the more computational efficient hard-gated categorical sampling of FoV-resolution patch configurations at each location and provide two differentiable solutions. We demonstrate the generical applicability on three vision datasets including Cityscapes, DeepGlobe aerial image and Gleason2019 histopathology dataset.

url_pdf: https://arxiv.org/pdf/2007.15124.pdf
url_code: https://github.com/lxasqjc/Foveation-Segmentation
doi: ""
featured: true
tags:
  - ""
projects:
  - foveation_ultrahigh
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2020-07-29T00:40:17.187Z
publishDate: 2020-07-29T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
