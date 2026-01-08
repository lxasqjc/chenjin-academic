---
title: Foveation for Segmentation of Mega-Pixel Histology Images
publication_types:
  - "1"
authors:
  - Chen Jin
  - Ryutaro Tanno
  - Moucheng Xu
  - Thomy Mertzanidou
  - Daniel C. Alexander
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *MICCAI, 2020*
publication_short: MICCAI, 2020
abstract: Segmenting histology images is challenging because of the sheer size of the images with millions or even billions of pixels. Typical solutions pre-process each histology image by dividing it into patches of fixed size and/or down-sampling to meet memory constraints. Such operations incur information loss in the field-of-view (FoV) (i.e., spatial coverage) and the image resolution. The impact on segmentation performance is, however, as yet understudied. In this work, we first show under typical memory constraints (e.g., 10G GPU memory) that the trade-off between FoV and resolution considerably affects segmentation performance on histology images, and its influence also varies spatially according to local patterns in different areas (see Fig. 1). Based on this insight, we then introduce foveation module, a learnable “dataloader” which, for a given histology image, adaptively chooses the ap- propriate configuration (FoV/resolution trade-off) of the input patch to feed to the downstream segmentation model at each spatial location (Fig. 1). The foveation module is jointly trained with the segmentation network to maximise the task performance. We demonstrate, on the Gleason2019 challenge dataset for histopathology segmentation, that the foveation module improves segmentation performance over the cases trained with patches of fixed FoV/resolution trade-off. Moreover, our model achieves better segmentation accuracy for the two most clinically important and ambiguous classes (Gleason Grade 3 and 4) than the top performers in the challenge by 13.1% and 7.5%, and improves on the average performance of 6 human experts by 6.5% and 7.5%.
draft: false
share: true
slides: ""

summary: We introduce a foveation module that dynamically adjusts patch FoV and resolution for ultra-high resolution image segmentation, achieving state-of-the-art results and significant accuracy boosts on challenging datasets.

url_pdf: https://discovery.ucl.ac.uk/id/eprint/10113531/1/paper1822.pdf
url_video: https://youtu.be/MxaO9DtNeEQ
url_code: https://github.com/lxasqjc/Foveation-Segmentation
doi: ""
featured: true
tags:
  - Medical Imaging
  - Segmentation
projects:
  - foveation
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: foveation.jpg
date: 2020-04-29T00:40:17.187Z
publishDate: 2020-04-29T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
